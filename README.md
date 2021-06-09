# Proceso para corregir infografías de Ilustrator

Las inforgrafías se tienen que hacer siguiendo las indicaciones de la [guía de visualización de datos](https://greenpeace.github.io/gpes-visualisations/infograph.html).

Una vez exportadas de Ilustrator los cambios en el SVG siguen casi siempre los pasos en este repositorio. Mirad los *[commits](https://github.com/greenpeace/gpes-instructions-svg-infographic/commits/main)* de este repositorio para ver todos los cambios en los ficheros SVG.

Una vez se puedan ver bien las infografías en los varios navegadores, se suben a al contenedor **gpes-static** en [Google Storage]("https://console.cloud.google.com/storage/browser/gpes-static;tab=objects?forceOnBucketsSortingFiltering=false&project=arcoiris-1348&prefix=&forceOnObjectsSortingFiltering=false").

Creas una carpeta y subes los archivos.

A tu equipo le pasas las URLs públicas. En este caso son:

- https://storage.googleapis.com/gpes-static/infografia-mapa-gas/mapa_gas_360px.svg
- https://storage.googleapis.com/gpes-static/infografia-mapa-gas/mapa_gas_510px.svg
- https://storage.googleapis.com/gpes-static/infografia-mapa-gas/mapa_gas_730px.svg
- https://storage.googleapis.com/gpes-static/infografia-mapa-gas/mapa_gas_1024px.svg

Por fin puedes basarte en [este código](https://jsfiddle.net/osvik/32kdtbg8/embedded/result,html/) para hacer un código que otras webs puedan usar. Para esta infografía el código **[está aquí](https://jsfiddle.net/greenpeace/951zmjov/)**.