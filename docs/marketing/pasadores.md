# Manual de uso de los pasadores

[Volver](marketing)

## Uso de pasadores

Para el uso de los pasadores, se ha generado un panel para gestionar los mismos.
Este panel permite cargar los pasadores que sean necesarios y colocar la información correspondiente a cada uno.


Para poder acceder a el panel de pasadores, deberas ingresar a [https://panel.bidcom.com.ar/pasadores](https://panel.bidcom.com.ar/pasadores)


Esta sección del panel, no cuenta con un acceso directo desde la home de panel, por lo que deberás ingresar a la url mencionada anteriormente. Pero si se lo ve útil, se podrá avisar a los desarrolladores para que agreguen un acceso directo.


## Listado de pasadores


En el listado de pasadores, se podrán ver todos los pasadores que se encuentren cargados en el sistema.


![Descripción de la imagen](/marketing/img/pasadores/Listado_pasadores.png)


Estos listados de pasadores cuentan con información de rápida visualización de cada pasador, como por ejemplo: Título del pasador, la fecha de inicio, la fecha de fin, la URL a la que aplica, la redirección que realiza, etc.


En los listados de pasadores, se podrán realizar diferentes acciones sobre los mismos. Una de ellas es la búsqueda de los pasadores por título o por el lugar en donde se aplica (también llamado slug).


![Descripción de la imagen](/marketing/img/pasadores/busqueda_pasadores.png)


También en los listados se podrán ordenar los pasadores según el slug para poder encontrarlos más fácilmente.


## Creación de pasadores


Para poder crear los pasadores, se deberá hacer click en el botón de `Crear Pasador` que se encuentra en la parte superior derecha de la view de listado de pasadores.


![Descripción de la imagen](/marketing/img/pasadores/boton_crear.png)


Al hacer click en este botón, se nos redireccionará a la view de creación de pasadores, en donde se deberá completar la información correspondiente a cada pasador.


![Descripción de la imagen](/marketing/img/pasadores/creacion_pasadores.png)


Para poder crear un pasador, vamos a tener que tener en cuenta que tipo de pasador queremos crear, y qué información queremos que contenga. Es por eso que se detallará a continuación cada uno de los pasadores que se pueden crear.

Tipos de pasadores o banners:

- [Pasador simple](#pasador-simple)
- [Pasador simple con fondo](#pasador-simple-con-fondo)
- [Pasador Doble](#pasador-doble)
- [Pasador Marcas](#pasador-marcas)
- [Banner Half](#banner-half)
- [Banner de Categorias](#banner-de-categorias)

## Pasador simple

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

![Descripción de la imagen](/marketing/img/pasadores/pasador_simple.png)

Esta pasador esta compuesto basicamente con un titulo, una boton de redireccion y por una serie de productos que se muestran en forma de carrusel. 

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Pasador simple`.
- **URL del pasador**: Este campo es el que indica a que URL se va a redireccionar al hacer click en el boton del pasador (el boton que dice `Ver mas`). 
- **Categorias**: Este campo es el que indica que categorias se van a mostrar en el carrusel del pasador. Para poder seleccionar las categorias, se debera hacer click en el boton de `Seleccionar categorias`. En esta seccion se podra colocar la cantidad de categorias de productos que se deseen agregar al carrusel de pasadores. 
- **Aplicados**: Este campo se debera incluir el slug de la URL que queremos que se muestre el pasador. Por ejemplo, si queremos que el pasador se muestre en la landing /hotsale, debemos seleccionar el slug de la landing, que en este caso es `hotsale`. 
- **Orientacion**: Este campo es el que indica la orientacion de las cards de productos que se muestran en el carrusel del pasador. En este caso de que las cards se visualizen de la manera en la que se muestra en la imagen, deberemos seleccionar `Vertical`. Pero si seleccionamos `Horizontal`, las cards se mostraran de la siguiente manera:

<!-- ![Descripción de la imagen](/marketing/img/pasadores/pasador_simple_horizontal.png) -->

- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.

## Pasador simple con fondo

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

![Descripción de la imagen](/marketing/img/pasadores/pasador_simple_fondo.png)

Esta pasador esta compuesto basicamente con un titulo, una boton de redireccion y por una serie de productos que se muestran en forma de carrusel.

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Pasador simple con fondo`.
- **Imagen**: En este campo deberiamos agregar la imagen que se usara de fondo para el pasador. Aconsejamos que esta imagen sea del tamaño de 1200px de ancho por 600px de alto (1200x600). Debes tener en cuenta, que la imagen que desees cargar en el pasador, debe estar descargada en tu equipo. Para poder cargar la imagen, deberas hacer click en el boton de `Subir archivo`, y se te abrira una ventana en donde podras seleccionar la imagen que desees cargar, desde tu equipo.
- **URL del pasador**: Este campo es el que indica a que URL se va a redireccionar al hacer click en el boton del pasador (el boton que dice `Ver mas`). Por ejemplo, en el caso de que queramos que el pasador se redireccione a la landing de hotsale, deberemos colocar el slug de la landing, que en este caso es `hotsale`.
- **Categorias**: Este campo es el que indica que categorias se van a mostrar en el carrusel del pasador. Para poder seleccionar las categorias, deberemos desplegar el selector de categorias, y seleccionar las categorias que deseemos agregar al carrusel de pasadores. No tiene limite la cantidad de categorias que se pueden agregar al carrusel.
- **Aplicados**: Este campo se debera incluir el slug de la URL que queremos que se muestre el pasador. Por ejemplo, si queremos que el pasador se muestre en la landing /hotsale, debemos seleccionar el slug de la landing, que en este caso es `hotsale`.
- **Activo**: Este campo es el que indica si el pasador se encuentra activo o no. En el caso de que queramos que el pasador se muestre, deberemos seleccionar `Si`. En el caso de que queramos que el pasador no se muestre, deberemos seleccionar `No`.
- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.

## Pasador Doble

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

![Descripción de la imagen](/marketing/img/pasadores/pasador_doble.png)

Este pasador esta compuesto basicamente por un titulo, una boton de redireccion y por una serie de productos que se muestran en forma de carrusel doble. Tambien contamos con una imagen, que se ubica en la parte lateral izquierda del pasador y que contiene una imagen/logo/frase que se desee mostrar, acompañado de un boton de redireccion.

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Pasador doble`.
- **Imagen**: En este campo deberiamos agregar la imagen que se usara de fondo para el pasador. Aconsejamos que esta imagen sea del tamaño de 1200px de ancho por 600px de alto (1200x600). Debes tener en cuenta, que la imagen que desees cargar en el pasador, debe estar descargada en tu equipo. Para poder cargar la imagen, deberas hacer click en el boton de `Subir archivo`, y se te abrira una ventana en donde podras seleccionar la imagen que desees cargar, desde tu equipo.
- **URL del pasador**: Este campo es el que indica a que URL se va a redireccionar al hacer click en el boton del pasador (el boton que dice `Ver mas`). Por ejemplo, en el caso de que queramos que el pasador se redireccione a la landing de hotsale, deberemos colocar el slug de la landing, que en este caso es `hotsale`.
- **Categorias**: Este campo es el que indica que categorias se van a mostrar en el carrusel del pasador. Para poder seleccionar las categorias, deberemos desplegar el selector de categorias, y seleccionar las categorias que deseemos agregar al carrusel de pasadores. No tiene limite la cantidad de categorias que se pueden agregar al carrusel.
- **Aplicados**: Este campo se debera incluir el slug de la URL que queremos que se muestre el pasador. Por ejemplo, si queremos que el pasador se muestre en la landing /hotsale, debemos seleccionar el slug de la landing, que en este caso es `hotsale`.
- **Activo**: Este campo es el que indica si el pasador se encuentra activo o no. En el caso de que queramos que el pasador se muestre, deberemos seleccionar `Si`. En el caso de que queramos que el pasador no se muestre, deberemos seleccionar `No`.
- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.

## Pasador Marcas

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

![Descripción de la imagen](/marketing/img/pasadores/pasador_marcas.png)

Este pasador esta compuesto basicamente por un titulo, y las cards de las marcas que se muestran en forma de carrusel. Cada una de ellas cuenta con imagenes de productos, y un boton de redireccion.

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Pasador de marcas`.
- **Marcas**: Este campo es el que indica que marcas se van a mostrar en el carrusel del pasador. Para poder seleccionar las marcas, deberemos desplegar el selector de marcas, y seleccionar las marcas que deseemos agregar al carrusel de pasadores. No tiene limite la cantidad de marcas que se pueden agregar al carrusel.
- **Aplicados**: Este campo se debera incluir el slug de la URL que queremos que se muestre el pasador. Por ejemplo, si queremos que el pasador se muestre en la landing /hotsale, debemos seleccionar el slug de la landing, que en este caso es `hotsale`.
- **Activo**: Este campo es el que indica si el pasador se encuentra activo o no. En el caso de que queramos que el pasador se muestre, deberemos seleccionar `Si`. En el caso de que queramos que el pasador no se muestre, deberemos seleccionar `No`.
- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.

## Banner Half

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

![Descripción de la imagen](/marketing/img/pasadores/banner_half.png)

Este pasador esta compuesto basicamente por dos imagenes. Y cuenta con un boton de redireccion, que puede ser opcinal.

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Banner Half`.
- **Imagen**: En este campo deberiamos agregar la imagen que se usara de fondo para el pasador. Aconsejamos que esta imagen sea del tamaño de 1200px de ancho por 600px de alto (1200x600). Debes tener en cuenta, que la imagen que desees cargar en el pasador, debe estar descargada en tu equipo. Para poder cargar la imagen, deberas hacer click en el boton de `Subir archivo`, y se te abrira una ventana en donde podras seleccionar la imagen que desees cargar, desde tu equipo.
- **Aplicar boton de redireccion**: Este campo es un campo opcional. En el caso de que queramos que el pasador cuente con un boton de redireccion, debemos clickear en el checkbox. En el caso de que no queramos que el pasador cuente con un boton de redireccion, debemos dejar el checkbox sin clickear.
    - **Posicion del boton**: Este campo es un select que podemos elegir entre dos opciones. La posicion del boton puede ser `Izquierda` o `Derecha`. 

    ![Boton lado derecho](/marketing/img/pasadores/posicion_boton_derecha.png)
    ![Boton lado izquierdo](/marketing/img/pasadores/posicion_boton_izquierda.png)

    - **Color de fondo del boton**: Este campo es un select que podemos elegir entre tres opciones de fondo para nuestros botones. Las opciones pueden ser `Color negro`, `Color blanco` o `Personalizado`.

    - **Color del boton en hexadecimal**: Este campo esta muy vinculado con el campo anterior `Color de fondo del boton`, y hasta actua de forma dinamica. En el caso que selecciones `Color negro` en ese campo, automaticamente se seteara el valor `#000000` en este campo. En el caso que selecciones `Color blanco` en ese campo, automaticamente se seteara el valor `#ffffff` en este campo. Pero en el caso que selecciones `Personalizado` en ese campo, se te habilitara este campo para que puedas colocar el color que desees en hexadecimal.

- **URL del pasador**: Este campo es el que indica a que URL se va a redireccionar al hacer click en el boton del pasador (el boton que dice `Ver mas`). Por ejemplo, en el caso de que queramos que el pasador se redireccione a la landing de hotsale, deberemos colocar el slug de la landing, que en este caso es `hotsale`.

- **Segunda Imagen**: En este campo deberiamos agregar la imagen que se usara de fondo para el pasador. Aconsejamos que esta imagen sea del tamaño de 1200px de ancho por 600px de alto (1200x600). Debes tener en cuenta, que la imagen que desees cargar en el pasador, debe estar descargada en tu equipo. Para poder cargar la imagen, deberas hacer click en el boton de `Subir archivo`, y se te abrira una ventana en donde podras seleccionar la imagen que desees cargar, desde tu equipo.

- **Aplicar boton de redireccion**: Este es un campo opcional. En el caso de que queramos que el pasador cuente con un boton de redireccion, debemos clickear en el checkbox. En el caso de que no queramos que el pasador cuente con un boton de redireccion, debemos dejar el checkout sin clickear. 
    - **Posicion del boton**: Este campo es un select que podemos elegir entre dos opciones. La posicion del boton puede ser `Izquierda` o `Derecha`.

    ![Boton lado derecho](/marketing/img/pasadores/posicion_boton_derecha.png)
    ![Boton lado izquierdo](/marketing/img/pasadores/posicion_boton_izquierda.png)

    - **Color de fondo del boton**: Este campo es un select que podemos elegir entre tres opciones de fondo para nuestros botones. Las opciones pueden ser `Color negro`, `Color blanco` o `Personalizado`.

    - **Color del boton en hexadecimal**: Este campo esta muy vinculado con el campo anterior `Color de fondo del boton`, y hasta actua de forma dinamica. En el caso que selecciones `Color negro` en ese campo, automaticamente se seteara el valor `#000000` en este campo. En el caso que selecciones `Color blanco` en ese campo, automaticamente se seteara el valor `#ffffff` en este campo. Pero en el caso que selecciones `Personalizado` en ese campo, se te habilitara este campo para que puedas colocar el color que desees en hexadecimal.

- **URL del segundo banner**: Este campo es el que indica a que URL se va a redireccionar al hacer click en el boton del pasador (el boton que dice `Ver mas`). Por ejemplo, en el caso de que queramos que el pasador se redireccione a la landing de hotsale, deberemos colocar el slug de la landing, que en este caso es `hotsale`.

- **Activo**: Este campo es el que indica si el pasador se encuentra activo o no. En el caso de que queramos que el pasador se muestre, deberemos seleccionar `Si`. En el caso de que queramos que el pasador no se muestre, deberemos seleccionar `No`.

- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.


## Banner de Categorias

Al seleccionar este pasador, se estara generando un pasador como el que se muestra a continuación:

En los banners de Mobile, se muestran de la siguiente manera:
![Banner de Categorias Mobile](/marketing/img/pasadores/banner_categorias_mobile.png)

En los banners de Desktop, se muestran de la siguiente manera:
![Banner de Categorias Desktop](/marketing/img/pasadores/banner_categorias_desktop.png)

Este pasador esta compuesto basicamente por un titulo, y las cards de cada una de las categorias de productos que se muestran. Cada una de ellas cuenta con su correspondiente imagen, la URL de la categoria, y el nombre de la categoria que se va a mostrar en pagina. 

Es por eso que desde el panel deberemos completar los siguientes campos:

- **Titulo**: Este campo es el que se muestra en la parte superior del pasador.
- **Fecha inicio**: Esta fecha es la que indica desde cuando se va a mostrar el pasador.
- **Fecha fin**: Esta fecha es la que indica hasta cuando se va a mostrar el pasador.
- **Tipo de pasador**: Este campo es el que indica que tipo de pasador se va a mostrar. En este caso, deberemos seleccionar `Banner de categorias`.
- **Categorias**: Este campo es el que contiene toda la informacion de las categorias que se van a mostrar en el pasador. En cada una de las categorias, debemos asegurarnos de que cuenten con la imagen de la categoria, la URL de la categoria, y el nombre de la categoria. 
- **Activo**: Este campo es el que indica si el pasador se encuentra activo o no. En el caso de que queramos que el pasador se muestre, deberemos seleccionar `Si`. En el caso de que queramos que el pasador no se muestre, deberemos seleccionar `No`.
- **Web**: Este campo es el que indica en que sitio web se va a mostrar el pasador. Podemos seleccionar la web de Bidcom, la web de Gadnic, o ambas.

## Consideraciones finales

Esperamos que esta documentación te sea de utilidad, y que puedas tener una buena experiencia en la utilizacion de los pasadores. Si tenes alguna duda, o necesitas ayuda con algo, no dudes en contactarte con cualquier integrante del equipo de desarrollo, que con gusto te vamos a ayudar.

[Volver](marketing)