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
  
  
  ### Formularios
  
  El Elemento HTML <label> representa una etiqueta para un elemento en una interfaz de usuario. Este puede estar asociado con un control ya sea mediante la utilizacion del atributo for, o ubicando el control dentro del elemento label
El elemento HTML <input> se usa para crear controles interactivos para formularios basados en la web con el fin de recibir datos del usuario. Hay disponible una amplia variedad de tipos de datos de entrada y widgets de control, que dependen del dispositivo y el agente de usuario (user agent).
  
   <form action="">
    <label for="nombre">
      <span>Cual es tu nombre?</span>
      <input type="text" id="nombre" placeholder="Tu nombre" required>
    </label>
    <label for="inicio-platzi">
      <span>Que dia comenzaste en Platzi?</span>
      <input type="date" id="inicio-platzi" >
    </label>
    <label for="horario">
      <span>En que horario estudias?</span>
      <input type="time" id="horario" >
    </label>
  </form>
  
  
  Para hacer que los campos del formulario se autocompleten solos con datos que ya ha usado antes el usuario (y están guardados en el navegador), se usa el atributo autocomplete dentro de la etiqueta input.

Para qué sirven distintos valores de el atributo autocomplete: https://developer.mozilla.org/es/docs/Web/HTML/Atributos/autocomplete

Para que los datos del campo sean obligatorios, se debe usar el atributo require en la etiqueta input.

Para crear inputs con una lista de varias opciones, se puede desarrollar de dos maneras diferentes:
.

Etiqueta <select>: Esta permite crear la lista, con las etiquetas <option>:
z.png.
.

Etiqueta <input list = “”>: De este modo, se puede utilizar una etiqueta <datalist> con etiquetas <option> dentro del input. De este modo, el usuario puede escribir dentro del input, y filtrar los resultados de la lista:
y.png.
  
  
