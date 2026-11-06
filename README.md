# BioMundos 2.0 — Simulador de evolución

Actualización de la versión inicial. Mantiene la simulación de población, ambiente, selección, mutaciones, creación de criaturas, genes cuantitativos, gráfica e historia.

## Novedades 2.0
- Registro de dos progenitores por descendiente y consulta de árbol familiar.
- Cuatro rasgos hereditarios de ejemplo: alas, caparazón, visión nocturna y bigotes sensoriales.
- Cada rasgo utiliza dos alelos: `A` dominante y `a` recesivo. El rasgo dominante se expresa con al menos una `A`; el recesivo requiere `a/a`.
- Los descendientes reciben al azar un alelo de cada progenitor; las mutaciones pueden cambiar un alelo.
- Algunos rasgos pueden influir ligeramente en la supervivencia ambiental.
- Se registra en la historia cuando aparece un rasgo expresado que no estaba presente en ninguno de los dos progenitores.

## Publicar en GitHub Pages desde Android
1. Abre tu repositorio en GitHub y entra a la pestaña **Code**.
2. Pulsa **Add file → Upload files**.
3. Descomprime este ZIP antes de subirlo, o abre la carpeta `evolucion_creaturas` y selecciona los cinco archivos.
4. Sube `index.html`, `styles.css`, `app.js`, `README.md` y `.nojekyll` a la raíz del repositorio (no dentro de otra carpeta).
5. Confirma con **Commit changes**. GitHub Pages actualizará el sitio automáticamente.
6. Recarga la página publicada. Si ves la versión anterior, recarga de nuevo o abre una pestaña privada.

## Archivos
- `index.html`: estructura de la página.
- `styles.css`: diseño adaptable a móviles y computadoras.
- `app.js`: simulación, herencia, alelos y linajes.
- `.nojekyll`: evita el procesamiento Jekyll de GitHub Pages.

## Nota educativa
Es un modelo didáctico, no un simulador biológico validado. La dominancia, los rasgos y la selección están simplificados. Los grupos genéticos mostrados como “especies” son aproximaciones por similitud y alimentación; no implementan aislamiento reproductivo ni el concepto biológico formal de especie. La gráfica histórica también es ilustrativa.
