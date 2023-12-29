# Guia de QUERYs en SQL 🧑🏻‍💻👩🏻‍💻

[Volver](/index)

#### Esta guia de querys, tiene como objetivo poder tener una guia de consulta rapida de las querys que mas usamos como equipo, para poder tener un seguimiento de las mismas, y poder reutilizarlas en el futuro. La idea es que esta seccion sea colaborativa, y que cada uno pueda ir agregando las querys frecuentes que crea que son utiles para el equipo.


### Buscar cupones del proyecto Sofia

```sql

SELECT * 
FROM checkoutbidcom.`CuponDescuento` 
WHERE nombre_creador = "proyecto_sofia" 
AND cupon = "modifica_nombre_cupon"

```

### Buscar compras realizadas con un cupon


```sql

SELECT pago.`idCarrito`, pago.`estado`, carrito.`cupon`, envio.`descripcion`, pago.`detalleEstado`, pago.`estado`, mediopago.`descripcion`
FROM checkoutbidcom.`CHK_Carrito` AS carrito
JOIN checkoutbidcom.`CHK_Pago` AS pago ON carrito.`id` = pago.`idCarrito`
JOIN checkoutbidcom.`CHK_MedioEnvio` AS envio ON carrito.`medio_envio_id` = envio.`id`
JOIN checkoutbidcom.`CHK_MedioPago` AS mediopago ON carrito.`medio_pago_id` = mediopago.`id`
WHERE cupon = "ingresa_tu_cupon"
AND pago.`estado` = "approved"
ORDER BY fecha DESC 

```