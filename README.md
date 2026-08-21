# Nightmares · portal público

Web estática multipágina para la campaña Midnight en Sharuum.

## Estructura

- `index.html`: portada y navegación.
- `historia.html`, `contexto.html`, `reglas.html`, `bestiario.html`, `personajes.html`, `cronologia.html`, `mapas.html` y `comic.html`: páginas independientes y reemplazables por paquetes versionados.
- `fichas.html`: frontera pública hacia el servidor protegido de fichas; no almacena datos.
- `styles.css`: sistema visual compartido.

## Frontera de publicación

Esta web excluye MOD005, secretos del Director, fichas privadas, catálogos mixtos y assets sin permiso web. El contenido de reglas publicable se limita al SRD 5.2.1 con atribución CC-BY-4.0 y a texto original aprobado. El Bestiario V3 incluye la ficha SRD del Cangrejo gigante; PNJ, antagonistas y mecánicas de ambientación sin licencia permanecen fuera.

## Actualización

Cada paquete entrante debe indicar propietario, versión, estado, ruta, hash, nivel de spoiler y permiso de publicación. Sustituir el contenido de una página no requiere rediseñar la portada.
