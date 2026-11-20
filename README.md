# LYtools · Catálogo

Archivo vivo del catálogo de **LYtools**, la aplicación de Liesky Vázquez
para encontrar programas, plugins y webs de IA para fotógrafos y editores.

- `catalogo.json` — las herramientas: nombre, para qué sirven, precio,
  página oficial y última versión verificada de cada una.
- `logos.json` — el logo de cada herramienta (PNG en base64), para que
  la aplicación los enseñe también sin conexión.

La aplicación LYtools baja `catalogo.json` de la dirección fija de este
repositorio cada vez que se abre con conexión; si hay una copia más
nueva, la guarda y trae los logos que le falten desde `logos.json`.
Sin conexión trabaja con la última copia guardada.

El catálogo lo mantiene al día Muse a petición de Liesky: cada versión
nueva trae las versiones comprobadas en las páginas oficiales.

© 2026 Liesky Vázquez
