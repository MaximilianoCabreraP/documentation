
# Errores vinculación EAN
[Volver](/index)

#### **Comunmente estos errores se produzcan por dos motivos:**

1. En productos viejos, no se registró el ean en la tabla de eans, por eso cuando un producto nuevo reserva un ean puede reservar uno que ya esta asignado a un producto en producción.
2. En productos con ref, los ref toman mal el EAN, toman un nuevo ean pero no lo reservan. Lo que deberían hacer es tomar el EAN del mismo producto nuevo. 

#### **Las queries que uso para buscar la información son las siguientes:**

```sql
    SET @ean = 0650414991175;

    set @sku1 = "CAFEXP02";
    set @sku2 = CONCAT("REF-", @sku1);
    -- set @sku2 = "CAFEXP02";

    SELECT *
    FROM ean
    WHERE sku = @sku1
    OR sku = @sku2
    OR ean = @ean;

    SELECT *
    FROM fichas
    WHERE codigo_aguila = @sku1
    OR codigo_aguila = @sku2
    OR ean = @ean;

    SELECT ID 'Tabla posts', codigo_aguila, ean, marca, post_status
    FROM bidcom.posts
    WHERE codigo_aguila = @sku1
    OR codigo_aguila = @sku2
    OR ean = @ean;
```

La primer query es para traer la info de la tabla EAN.
La segunda es para ver la información que registraron en ficas. Aca es comunmente donde está el error, ya que la ficha la hacen con el ean equivocado y despues se corrige.
La ultima query es más que nada para validar que esté todo ok en el producto que está en posts. Valido mas que nada el codigo_aguila y el ean que tienen.

#### **Según los errores definidos mas arriba, hay dos soluciones:**
1. Cuando pasa esto, comunmente el error está en la tabla ean. El producto viejo no registró el ean y otro nuevo lo tiene reservado. Lo que hago es que el producto viejo tome el ean que le corresponde. Y al producto nuevo le asigno un nuevo ean (Busco en la tabla un ean que tenga estado en 0 y que en sku esté vacio)
2. Esto pasa cuando en la ficha crean un producto REF y le asignan un nuevo ean en vez de tomar el del producto nuevo. Lo que hago es cambiar el ean en la ficha por el mismo que tiene el producto nuevo.

#### **Respuestas al analista que realiza la consulta**
1. En este caso, el analista va a tener que actualizar la página para que le tome el nuevo EAN, de esa forma se soluciona su conflicto y puede crear la ficha.
2. Este es el caso mas simple, no tiene que actualizar nada, con volver a ejecutar el guardado de la ficha ya debería dejarlo avanzar.