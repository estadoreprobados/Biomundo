# BioMundos — Simulador de evolución

Página web educativa para experimentar con criaturas ficticias, genes heredables, mutaciones, supervivencia y formación de grupos genéticos.

## Publicar en GitHub Pages (desde Android o computadora)

1. Descarga y descomprime `BioMundos-GitHub.zip`.
2. En GitHub crea un repositorio nuevo, por ejemplo `biomundos`.
3. Sube **todos los archivos y carpetas** que están dentro de la carpeta `evolucion_creaturas` (no subas la carpeta ZIP dentro del repositorio).
4. En el repositorio abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Elige la rama `main` y la carpeta `/ (root)`. Pulsa **Save**.
7. Espera unos minutos. GitHub mostrará el enlace público de tu página en Settings → Pages.

## Archivos

- `index.html`: estructura de la página.
- `styles.css`: diseño adaptable a celulares y computadoras.
- `app.js`: lógica de simulación, genes, herencia, mutaciones y selección.

## Cómo experimentar

- Pulsa **Avanzar 1 generación** para observar un ciclo.
- Pulsa **Simular** para avanzar automáticamente; puedes pausarlo.
- Cambia temperatura, alimento, depredación y tasa de mutación. Pulsa **Aplicar cambios**.
- Crea organismos y ajusta sus genes para iniciar poblaciones con características diferentes.
- Selecciona criaturas para consultar sus genes y habilidades.

## Modelo científico

Es una simulación didáctica y simplificada. Los genes se representan con valores de 0 a 100. La descendencia combina valores de dos progenitores y puede presentar mutaciones. La supervivencia depende de una puntuación ambiental aproximada. Los grupos de especie son agrupaciones visuales basadas en dieta y similitud genética; no equivalen a una definición biológica formal de especie ni a una simulación genética realista.

No requiere servidor, base de datos, claves API ni instalación. Se ejecuta en el navegador.
