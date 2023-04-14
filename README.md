# semantica-HTML
Estructuras para buenas practicas de desarrollo

Tamaño máximo recomendado para una imágen:

70kb a 100kb   // no deben las imagenes pesar mas de 1mega en ma web
###  imágenes:

Herramientas para optimizar

Tiny PNG: Comprime el tamaño de una imagen, para hacerla más ligera.

Verefix: Elimina los metadatos de una imagen, para reducir su tamaño.

### Videos

La etiqueta <video>, tiene algunos atributos como:
.

controls: agrega al video los controles necesarios para reproducir, pausar y adelantar.

preload = auto: hace que el navegador descargue el video, en el momento en el que se acceda a la página.

.
La etiqueta <source>, se puede colocar dentro de una etiqueta <video> varias veces, para especificar diferentes rutas. Esto para asegurar que cualquier navegador pueda mostrar el video.
  
  <video src=””></video>: etiqueta de video que permite renderizar el video, pero por si solo lo carga, pero no tiene botones de play o pausa, para ello:

Controls: es un atributo que permite tener los controles para manipular el video en el navegador.

Preload=”auto”: atributo que ayuda para que el video se empiece a renderizar, pero no hace que se reproduzca solo, ya no se puede.

#t=10,60: es una extensipon de sourse donde se especifica cuando quiero que arranque el video y donde finalice.

<source />: etiqueta que permite especificar diferentes rutas, esto con el fin de asegurar que el navegador pueda mostrar el video.
  
  
