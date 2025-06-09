# CSS-GRID  
display: flex | inline-flex

flex-direction: row | row-reverse | column | column-reverse

flex-wrap: nowrap | wrap | wrap-reverse

flex-flow: <direction> <wrap>

justify-content: flex-start | center | space-between | space-around | space-evenly

align-items: stretch | flex-start | center | baseline

align-content: stretch | flex-start | center | space-between | space-around

Ítems Flex (hijos):

order: <integer>

flex-grow: <number>

flex-shrink: <number>

flex-basis: <length> | auto

flex: <grow> <shrink> <basis>

align-self: auto | flex-start | center | etc.

🔹 CSS Grid (Grid Layout Module)
Contenedor Grid (padre):

display: grid | inline-grid

grid-template-columns, grid-template-rows

grid-template-areas

gap, row-gap, column-gap

justify-items, align-items, place-items

justify-content, align-content, place-content

grid-auto-rows, grid-auto-columns, grid-auto-flow

grid: <rows> / <columns> [ areas ]

Ítems Grid (hijos):

grid-column-start/end, grid-row-start/end

grid-column, grid-row

grid-area

justify-self, align-self, place-self

🧠 Notas Avanzadas
Unidades fr, uso de minmax(), repeat(auto-fit, ...)

Nombres de líneas para posicionamiento preciso

División de diseño en áreas usando grid-template-areas

Combinación recomendada: Grid para la estructura general y Flexbox dentro de áreas para alineación interna responsiva

🖌️ Estilo Visual Recomendado
Encabezados diferenciados con iconografía y color

Cajas o bloques para cada propiedad en Grid/Flexbox

Ejemplos de código estilizados con fondo suave y tipografía monoespaciada

Diagramas simples que ilustren ejes y alineamientos (los mismos del PDF de CSS‑Tricks funcionarán muy bien)

