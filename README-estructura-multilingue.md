# Estructura multilingüe AXIS-COG

## Carpetas

- `index.html`: redirige automáticamente a la versión española.
- `es/index.html`: versión española principal.
- `en/index.html`: versión inglesa preparada para traducción.
- `pt/index.html`: versión portuguesa preparada para traducción.
- `assets/`: carpeta para favicon, imágenes y recursos compartidos.

## Cómo subirlo

Sube toda la carpeta `axis-cog-multilingual` al servidor. La URL principal puede apuntar al `index.html` de la raíz.

Ejemplo:

```text
/
  index.html
  favicon.svg
  /es/index.html
  /en/index.html
  /pt/index.html
  /assets/
```

## Cómo traducir

Traduce únicamente el contenido visible dentro de `en/index.html` y `pt/index.html`. Mantén iguales:

- clases CSS
- ids de secciones
- rutas de enlaces internos
- estructura de tarjetas
- nombres de archivos

Los botones ES / EN / PT ya enlazan entre versiones.
