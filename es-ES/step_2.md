## Crear un enlace a otra página web en el mismo proyecto

Los proyectos web pueden estar formados por un montón de archivos HTML enlazados entre si.

+ Abre este trinket: <a href="http://jumpto.cc/web-rooms" target="_blank">jumpto.cc/web-rooms</a>. Si estás leyendo este proyecto en línea, también puedes usar el siguiente trinket incrustado:

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/ef608f0733" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

+ El trinket debería ejecutarse automáticamente, y tú deberías encontrarte en el vestíbulo:

	![screenshot](images/rooms-hall-start.png)

+ Fíjate en la lista de pestañas de este trinket. ¿Ves la pestaña`tvroom.html`? Haz clic en ella.

	![screenshot](images/rooms-tvroom-html.png)

	Este es otro archivo html dentro del mismo proyecto.


+ Para poder llegar a `tvroom.html` tienes que añadir un enlace en `index.html`.

	Añade el código subrayado al `<div>` que contiene la categoría ("class") `room`:

	![screenshot](images/rooms-link-tvroom.png)

+ Prueba tu trinket haciendo clic en el enlace __Sala TV__ para ver la página web `tvroom.html`.

	Fíjate que `tvroom.html` también tiene su propio archivo de estilo `tvroom.css`, que define el diseño de esta página.

	![screenshot](images/rooms-tvroom-unstyled.png)
	
