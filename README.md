# Fortnite Daily - Periódico Digital (UT2.A3)

Nombre de la página: Fortnite Daily
Tematica: Periódico digital sobre noticias, competitivo (FNCS), colaboraciones y actualizaciones de Fortnite.
Autor: Michael Steven Ospina Ocampo

Explicación sobre los siguientes conceptos:

1. ¿Cuál es la diferencia entre un elemento de bloque y uno en línea?
Un elemento de bloque (block) ocupa todo el ancho disponible de su contenedor y siempre empieza en una línea nueva (como `<div>`, `<p>`, `<h2>` o `<h3>`). En cambio, un elemento en línea (inline) solo ocupa el espacio necesario para su contenido y se mantiene dentro de la misma línea de texto sin provocar saltos (como `<span>`, `<strong>` o `<a>`).

2. ¿Qué diferencia existe entre `class` e `id`?
El atributo `id` es un identificador único que solo puede aplicarse a un elemento concreto en toda la página (en CSS se selecciona con `#`), ideal para secciones principales como `#cabecera`, `#noticias` o `#pie`. El atributo `class` permite agrupar y reutilizar los mismos estilos en varios elementos distintos a la vez (en CSS se selecciona con `.`), como `.noticia` o `.categoria`.

3. ¿Qué diferencia hay entre `margin` y `padding`?
El `padding` (relleno) es el espacio interno que separa el contenido del elemento (texto o imagen) de su propio borde (`border`). El `margin` (margen) es el espacio externo que separa el borde de esa caja respecto a los demás elementos de la página.

4. ¿Para qué sirve `box-sizing: border-box`?
Sirve para que el navegador calcule el ancho (`width`) y el alto (`height`) total de una caja incluyendo dentro de esa medida el contenido, el `padding` y el `border`. De esta forma, al añadir bordes o relleno a un elemento, la caja no aumenta su tamaño total ni descuadra la maquetación.