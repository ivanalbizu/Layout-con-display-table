# Layout con display table

## Versión desktop
Se maqueta usando display table para permitir que las columnas de una misma fila mantengan la misma altura, independientemente de su contenido. Las columnas de cada fila crecen en altura según crezcan sus columnas "hermanas".
Soporte IE9+

## Versión mobile
Se redefine a flexbox para poder usar la propiedad "order" a cada elemento de una fila
En dispositivo móviles flexbox está bien soportado [Caniuse](https://caniuse.com/#feat=flexbox)

[Demo](http://mentiraspoliticas.es/projects/grid-table/grid-table.html)