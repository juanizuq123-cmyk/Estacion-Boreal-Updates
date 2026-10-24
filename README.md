# Estación Boreal — canal de perfiles

Repositorio público dedicado a publicar los packs del cliente Estación Boreal y Boreal Constructor. Cada publicación se valida contra Minecraft 26.1.2 y NeoForge 26.1.2.95, se firma con una clave del canal Boreal y actualiza su manifiesto estable en GitHub Pages.

Para publicar una versión, crear una release `estacion-boreal-X.Y.Z` o `boreal-constructor-X.Y.Z` que contenga `profile-input.zip` con `manifest.json` y el pack indicado. La acción valida el contenido, firma el manifiesto, publica archivos inmutables y avanza el canal estable. No cargar claves privadas al repositorio.
