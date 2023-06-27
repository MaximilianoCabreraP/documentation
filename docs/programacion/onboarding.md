# Proceso de Onbording 🧑🏻‍💻👩🏻‍💻

[Volver](/index)

¡Bienvenido a equipo! De parte del equipo de Bidcom estamos muy contentos de tenerte con nosotros en nuestro team 🚀
Esta documentacion tiene como principal objetivo que puedas contar con todas las herramientas necesarias que vas a usar en tu dia a dia, y que sea muy sencillo ambientarte en el equipo. 

## Programas y aplicaciones que vas a usar

### Visual Studio Code

Desde el equipo de desarrollo, recomendamos la utilizacion del IDE Visual Studio Code. Por supuesto, si estas acostumbrado a usar otro Entorno de Desarrollo Integrado, podes seguir usandolo sin problemas.
El equipo de desarrollo, lo suele usar bastante, con la facilidades intuitivas que brinda la herramienta y por la gran cantidad de extensiones que tiene. 

Podes descargarlo desde [este link](https://code.visualstudio.com/).

Las extensiones que mas utilizamos como equipo son:

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

Esta extension te va a permitir tener una mejor gestion de los cambios que se fueron modificando como equipo, ya que nos permite tener mas info sobre el commit, quien lo hizo, cuando, el comentario del mismo y hasta que archivos fueron modificados.

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)

Esta extension te va a permitir tener una visualizacion mas grafica de los errores de sintaxis que tengamos en nuestro archivo, ya que nos va realtar con un color rojo los errores que tengamos. Es espealmente util para los errores tipicos en PHP, como por ejemplo, el olvido de un punto y coma.

- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

Esta extension es bastante usada cuando como equipo tenemos una reunion y son varias las personas que queremos ir modificando el mismo. Esta extension nos permite compartir nuestro codigo con otras personas, y que todos podamos estar conectados, teniendo un seguimiento en tiempo real de los cambios que se van produciendo.

- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

Esta es una extension que la usamos bastante como equipo, ya que nos permite tener diferenciacion en los comentarios. Muchas veces se comenta el codigo en diferntes partes que en el futuro requieran una optimizacion, o codigo que necesitan deprecarse en el futuro. Y esta extension, justamente nos permite hacer mas visible esos comentarios, para que no se nos pase por alto.

- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

Esta es una extension que es bastante util, ya que si queremos probar alguna funcionalidad de nuestro codigo, podemos ejecutarlo desde la misma consola de Visual Studio Code, sin necesidad de tener que instalar otros programas, o usar algunos en linea. 

### Git/GitHub Desktop

Esta es una aplicacion de escritorio que es muy util, ya que nos permite usar todas las facilidades de Git, pero de una forma mas intuitiva y mas visual, lo cual nos es muy util especialmente al momento de querer hacer algunas acciones un poco mas complejas como un merge, algun revert, crear pull request, etc.

Podes descargarlo desde [este link](https://desktop.github.com/).

### Mattermost (tambien llamado amigablemente como Slock 🤣)

Esta es una aplicacion de mensajeria que utilizamos con el equipo, ya que nos permite tener un chat grupal, y tambien poder tener conversaciones privadas con otros miembros del equipo. Es muy util para poder tener una comunicacion mas fluida, y tambien para poder compartir archivos, imagenes, etc.

Podes descargarlo desde [este link](https://mattermost.com/download/).

### ClickUp

Esta es una aplicacion que utilizamos para poder gestionar las tareas que tenemos como equipo. Es muy util para poder tener un seguimiento de las tareas que tenemos pendientes, las que estan en proceso, y las que ya estan terminadas. Tambien la utilizamos para proponer nuevas ideas o mejoras, y para poder tener un seguimiento de las mismas. En los ticktes que se crean, tienen que estar bien detalladas las tareas a realizar, y el tiempo que estimamos en completarlas. 

Podes descargarlo desde [este link](https://clickup.com/).

### Navegadores

Sin lugar a dudas, tener a disposicion varios navegadores es muy util, ya que nos permite poder probar las funcionalidades que vamos desarrollando en diferentes navegadores, y asi poder asegurarnos que todo funcione correctamente.

Los navegadores que te recomendamos que tengas instalados son:

- [Google Chrome](https://www.google.com/intl/es/chrome/)
- [Mozilla Firefox](https://www.mozilla.org/es-AR/firefox/new/)
- [Safari](https://support.apple.com/es_AR/downloads/safari)

### Bases de datos

Es necesario que tambien puedas configurar tu gestor de bases de datos que uses, para poder conectarte a las bases de datos que tenemos en el servidor. En el equipo utilizamos la herramienta [Navicat](https://www.navicat.com/en/download/navicat-premium) y tambien [SQLYogs](https://sqlyog.en.softonic.com/). Pero si tienen alguna otra herramienta que te guste mas, podes usarla sin problemas.

Una vez que ya tengas instalada la aplicacion de escritorio, vas a tener que configurar la conexion a la base de datos. Los datos de conexion como lo son la direccion del host, la password, y demas, puedes pedirlos a cualquier integrante del equipo de desarrollo.

## Descripciones generales de los entornos de desarrollo. 

- **Panel**: Es el entorno de desarrollo que usamos para poder administrar ciertas tareas operativas de la empresa, como lo son la gestion de los detalles de los productos que tenemos en venta en la web, la gestion de procesos internos como los son la creacion de categorias de productos, la creacion de pasadores que son utilizados en las landings de fechas especiales como HotSale, CyberModay, etc. Ramas disponibles de desarrollo son `master`, `develop`, `test`, `santi`, `meme`, `beta` y `test-old`.
Para poder acceder a alguna de las ramas de desarrollo de este entorno, debes colocar en la url de tu navegador, el entorno que estas usando. Por ejemplo: panel-dev.bidcom.com.ar, panel-test.bidcom.com.ar, panel-santi.bidcom.com.ar, etc. Con la excepcion de la rama master. A esta rama, accedes directamente cuando entras en el panel, sin necesidad de colocar nada en la url. 

- **NewHome**: Es el entorno de desarrollo que usamos para poder efectuar nuevas funcionalidades o mejoras en la web de [Bidcom](https://www.bidcom.com.ar). Este proyecto contiene todo el codigo de la web, que gestiona los procesos de precios, productos, categorias, etc. Ramas disponibles de desarrollo son `master`, `develop`, `test`, `santi`, `meme`, `attr`, `beta` y `design`. Para acceder a este entorno, debes colocar en la url de tu navegador, el entorno que estas usando. Por ejemplo: home-dev.bidcom.com.ar, home-test.bidcom.com.ar, home-santi.bidcom.com.ar, etc. Con la excepcion de la rama master. A esta rama, accedes directamente cuando entras en la web de [Bidcom](https://www.bidcom.com.ar), sin necesidad de colocar nada en la url.

- **NewGadnic**: Es el entorno de desarrollo en el que implementamos la web de [Gadnic](https://www.gadnic.com). Este proyecto contiene todo el codigo de la web, muy similar al proyecto de NewHome, que gestiona los procesos de precios, productos, categorias, etc. Ramas disponibles de desarrollo son `master`, `develop` y `test`. Para acceder a este entorno, debes colocar en la url de tu navegador, el entorno que estas usando. Por ejemplo: dev.gadnic.com.ar, test.gadnic.com.ar, etc. Con la excepcion de la rama master. A esta rama, accedes directamente cuando entras en la web de [Gadnic](https://www.gadnic.com.ar), sin necesidad de colocar nada en la url.

- **Checkout**: En este entorno se calculan y se establecen los precios finales de los productos a la hora de realizar una compra. Tambien se gestionan los datos de los usuarios, y se establecen la forma de entrega de los productos. La forma de acceder a este entorno es a traves de la web de [Bidcom](https://www.bidcom.com.ar), simulando la compra de un producto. Sino puedes acceder directamente desde [este link](https://checkout.bidcom.com.ar), con la diferencia de que no vas a contar con productos en tu carrito de compras, y por ende no vas a poder simular una compra, navegando por este entorno. 
Ramas disponibles de desarrollo son `master`, `develop`, `test`, `attr`, `meme`, `santi`, `meme-old` y `develop-old`.
Para poder acceder a alguna de las ramas de desarrollo de este entorno, debes colocar en la url de tu navegador, el entorno que estas usando. Por ejemplo: checkout-dev.bidcom.com.ar, checkout-test.bidcom.com.ar, checkout-santi.bidcom.com.ar, etc. Con la excepcion de la rama master. A esta rama, accedes directamente cuando entras en el checkout, sin necesidad de colocar nada en la url.

## Considereaciones finales.

Esperamos que esta documentacion te sea de utilidad, y que puedas tener una buena experiencia en el equipo. Si tenes alguna duda, o necesitas ayuda con algo, no dudes en contactarte con cualquier integrante del equipo de desarrollo, que con gusto te vamos a ayudar.

[Volver](/index)