# Sitio informativo de respaldo cifrado

Este directorio contiene las páginas estáticas para `backup.moonbox.info`:

- `index.html`: página principal.
- `privacy/index.html`: política de privacidad.
- `terms/index.html`: términos de servicio.
- `styles.css`: estilos locales accesibles.
- `CNAME`: dominio personalizado para GitHub Pages.

## Publicación en GitHub Pages

1. Copia el contenido de este directorio a la raíz de un repositorio destinado al sitio.
2. En la configuración del repositorio, habilita GitHub Pages para la rama y carpeta que contienen estos archivos.
3. Configura `backup.moonbox.info` como dominio personalizado en GitHub Pages. Conserva `CNAME` en la raíz publicada.
4. En el proveedor DNS, crea los registros que indique GitHub Pages para el dominio elegido y espera la propagación. Habilita HTTPS desde la configuración de Pages cuando esté disponible.
5. Abre la página principal, `/privacy/` y `/terms/` por HTTPS para confirmar que las rutas y el dominio funcionan.

No se incluyen credenciales, secretos, scripts externos ni recursos alojados fuera del sitio. Antes de publicar, confirma que las declaraciones sobre permisos, cifrado, claves, conservación y servicios técnicos describen el comportamiento real de la aplicación.
