<!-- MISION 1 - EL DESPERTAR DEL DOM / HUGO COBOS GUTIERREZ INSO3ºB -->
## Uso de IA
He usado ChatGPT como herramienta de apoyo principalmente para la parte de JavaScript, ya que la pagina esta basada en una pagina similar que hice en primero sin JavaScript, que era una tienda de videojuegos mas completa y con un HTML y CSS mas avanzado. Por este motivo, el HTML y el CSS ya estaban pensados. Lo que he hecho ha sido reducir esa pagina y añadirle una interactividad con JS que no tenia.

He usado la IA principalmente para implementar los filtros de peliculas, tanto por seccion como por titulo, utilizando "classList" y eventos.

Tambien he pedido ayuda para implementar el modo oscuro, con el evento "keydown" y "classList.toggle" que ponia en la guia de arranque. Y ya que estabamos me ha dado la parte de css correspondiente al modo oscuro.

Ejemplos de prompts reales:

* "como hago para filtrar las peliculas por categorias con JavaScript"
* "como hago un buscador por el nombre"
* "como hago el modo oscuro con keydown y classList.toggle"

No he usado nada fuera de mi conocimiento, o que no haya aprendido en primero o en el tema 1, simplemente he requerido la ayuda para poder resolver mis dudas y obtener una solucion que yo entendiera cuando no me venia a la cabeza la solucion.

## Autopsia
1. Para el buscador he decidido utilizar un evento "input" para que las peliculas se filtren mientras escribo el nombre a tiempo real en la funcion del js. Descarte utilizar un boton de buscar cuando terminas de escribir porque de esta forma es mas rapida y mas visual.

2. He creado una funcion "mostrarCategoria()" que recibe por parametro la categoria para poder filtrar las peliculas. Asi no he tenido que duplicar codigo para cada categoria.