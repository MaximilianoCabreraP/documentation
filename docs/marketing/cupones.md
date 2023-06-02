# Manual de uso de cupones

[Volver](marketing)

## Uso de cupones

Para el uso de cupones, se ha generado un panel para gestionar el mismo. 
Este panel permite cargar los cupones que sean necesarios y colocar la informacion correspondiente a cada uno. 

Para poder acceder a el panel de cupones, deberas ingresar a [https://panel.bidcom.com.ar/cupones](https://panel.bidcom.com.ar/cupones)

Asi mismo tambien se agrego un acceso directo a este panel desde la home de panel. 

![Descripción de la imagen](/programacion/img/cupones/Acceso_directo_panel.png)

## Listado de cupones 

En el listado de cupones, se podran ver todos los cupones que se encuentren cargados en el sistema.

![Descripción de la imagen](/programacion/img/cupones/Listado_cupones.png)

Estos listados de cupones cuentan con informacion rapida de cada cupon, como por ejemplo: Nombre, Tipo de pago, Descuento, Voucher, Fecha de inicio, Fecha de fin, Aplicado a, etc.

Y cuenta con una columna especifica llamada "Acciones". Esta columna cuenta con accesos directos a acciones especificas. 

![Descripción de la imagen](/programacion/img/cupones/Acciones.png)

En el caso de querer editar un cupon, o ver mas detalles del mismo, se debera hacer click en el icono de "Lapiz" que se encuentra en la columna "Acciones".
En el caso de que el cupon se encuentre activo y se quiera desactivar, se debera hacer click en el icono de "Tacho de Basura" que se encuentra en la columna "Acciones". 
Y en el caso de que el cupon se encuentre desactivado y se quiera activar, se debera hacer click en el icono de "Check" que se encuentra en la columna "Acciones".

## Pasos para la creacion de cupones

Para crear un cupon, deberas ingresar a la seccion de cupones y hacer click en el boton "Crear cupon"

![Descripción de la imagen](/programacion/img/cupones/Creacion_cupones.png)

Una vez dentro de la pagina de crear cupon, deberas completar los siguientes campos:
### - **Nombre** (Campo Obligatorio)

En este campo se debera colocar el nombre del cupon, el cual sera el que se mostrara en el panel de cupones. Un detalle a tener en cuenta es que el cupon NO DEBE CONTENER ESPACIOS, en caso de que el cupon tenga mas de una palabra, se debera colocar un guion bajo entre cada palabra. En este campo se debera incluir cualquier caracter alfanumerico.

### - **Fuente** (Campo no obligatorio)

El campo de fuentes es un espacio opcional, en el cual se podra colocar la fuente del cupon. Con fuente nos referimos a la persona que otorgo el cupon. 

### - **Tipo de pago** (Campo Obligatorio) 

En este campo deberemos seleccionar el tipo de pago que aplicara el cupon. Los tipos de pago que se pueden seleccionar son los siguientes:
1_ Todos: Este tipo de pago aplica a todos los tipos de pago ( Pagos en efectivo, pagos con tarjeta de credito y pagos con tarjeta de debito).
2_ Efectivo: Este tipo de pago aplica a los pagos realizados en efectivo.
3_ Credito: Este tipo de pago aplica a los pagos realizados con tarjeta de credito.
4_ Debito: Este tipo de pago aplica a los pagos realizado con tarjeta de debito.

### - **Descuento** (Campo Obligatorio)

En este campo se debera colocar el descuento que aplicara el cupon. El descuento se debera colocar en porcentaje, por ejemplo: 5%, 10%, 15%, etc.

### - **Voucher** (Campo no obligatorio)

En este campo, se debera colocar el voucher del cupon. El voucher debera ser un monto fijo en pesos argentinos.

### - **Fecha de inicio** (Campo Obligatorio)

En este campo se debera colocar la fecha de inicio del cupon. Esta fecha sera la fecha en la cual el cupon comenzara a ser valido. Por defecto, en la pagina, se va a ver el dia de hoy como fecha de inicio, pero se podra modificar la fecha de inicio a gusto.

### - **Fecha de fin** (Campo Obligatorio)

En este campo se debera colocar la fecha de fin del cupon. Esta fecha sera la fecha en la cual el cupon dejara de ser valido. En el caso de no ingresar una fecha de fin, el sistema colocara como fecha fin, el periodo de 3 (tres) meses a partir de la fecha de inicio.

### - **Aplicado a** (Campo Obligatorio)

![Aplicado a](/programacion/img/cupones/Seccion_aplicados.png)

En este campo se debera seleccionar a que tipo de productos se aplicara el cupon. Los tipos de productos que se pueden seleccionar son los siguientes:

1_ Todos los productos de Bidcom y Gadnic: Este tipo de producto aplica a todos los productos, tanto los de Bidcom, como los de Gadnic. En el caso de que querer colocar una restriccion a un producto en particular, se podra colocar en la seccion que se desplegara llamada "Restricciones". Esta seccion de "Restricciones" sera un campo opcional. 

2_ Todos los productos de Gadnic: Este tipo de producto aplica a todos los productos de Gadnic.

3_ SKU: Este tipo de producto aplica a uno o varios SKU especificos. En este caso, se debera colocar el o los SKU a los cuales se aplicara el cupon.

4_ Categoria: Este tipo de producto aplica a una o varias categorias especificas. En este caso, se debera colocar la o las categorias a las cuales se aplicara el cupon. En el caso de que elegir el cupon por categoria, tambien se podra elegir si el cupon tendra restricciones de algun producto en particular dentro de la categoria seleccionada. Para ello, se debera ingresar en la seccion de "Restricciones" y colocar el o los SKU a los cuales se aplicara el cupon. Es importante mencionar que esta seccion de "Restricciones" sera un campo opcional.

Luego de haber completado todos los campos, se debera hacer click en el boton "Guardar" para guardar el cupon. Y listo, el cupon ya estara creado y se podra usar al momento de realizar una compra.

## Comentarios finales

Este panel fue armado para que sea lo mas simple posible, para que cualquier persona pueda crear un cupon sin ningun tipo de problema.
De todas formas, si se llega a tener algun problema con el panel, o si se necesita plantear un punto de mejora,  se debera contactar con el area de programacion para que se pueda solucionar el problema. Recorda hacerlo por Bitrix24. 

