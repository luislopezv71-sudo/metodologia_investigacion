# Metodología de la Investigación — Artefactos universitarios

## Estructura

- `index.html`: portal principal.
- `unidad_I/index.html`: artefacto interactivo completo.
- `unidad_I/recursos.json`: enlaces configurables a video e infografía.

## Publicación en GitHub Pages

Sube estos archivos conservando sus rutas, activa GitHub Pages desde la rama principal y abre la URL del repositorio. No requiere frameworks, compilación ni servidor.

## Configuración de recursos

Edita `unidad_I/recursos.json` para incorporar las URLs públicas del video y la infografía. Se admiten videos de YouTube y enlaces de Drive con vista previa embebida cuando sus permisos lo permiten. Para infografía gráfica se admiten URLs públicas directas PNG/JPG/WebP/SVG. Un recurso alojado en Drive puede abrirse en nueva pestaña, pero no necesariamente mostrarse como imagen integrada. Cambios realizados solo en la computadora del docente no modifican la versión pública hasta subir y publicar el JSON actualizado.

## Consideraciones

La ficha se guarda en `localStorage` del navegador mediante botón; no hay sincronización entre dispositivos, servidor ni registro institucional de notas. El cuestionario es formativo. Se recomienda publicar mediante HTTPS. Para pruebas locales, abrir `index.html` directamente permite estudiar; puede ser necesario servir archivos con un servidor local para cargar `recursos.json` por restricciones `file://`.
