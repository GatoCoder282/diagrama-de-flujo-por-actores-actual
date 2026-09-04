# Procedimiento actual — extracción y estructuración DataX

Diagrama de flujo por actores (swimlane) del procedimiento actual de incorporación
de una fuente pública, desde el ticket hasta la entrega al repositorio analítico.

Carriles: Sistema de tickets, Desarrollador externo, Suite de pruebas automatizadas,
Motor de ejecución, Validador humano, Apache Airflow.

## Ver el diagrama

`index.html` renderiza el diagrama con Mermaid y permite zoom/pan libre sin
pérdida de calidad (SVG). Abrir directamente en el navegador o desplegar en Netlify:

1. Conectar este repositorio en Netlify.
2. Build command: (vacío)
3. Publish directory: `.`

No requiere paso de build ni dependencias — es HTML estático que carga Mermaid
y svg-pan-zoom desde CDN.

## Editar el diagrama

El código Mermaid está embebido directamente en `index.html`, dentro del `div#diagram`.
También existe una copia independiente en `flujograma_swimlane.mmd` (carpeta TG1) para
edición rápida en [mermaid.live](https://mermaid.live).
