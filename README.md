# Contraluz Pro · Android

Copia de Contraluz Pro preparada para empaquetarse como app Android (TWA con PWABuilder).
El repositorio original `contraluz-pro` no se toca.

- Web: se publica como Static Site en Render (sin build, carpeta raíz).
- Iconos en PNG (`icon-192.png`, `icon-512.png`) en lugar de base64 dentro del manifest.
- `.well-known/assetlinks.json` se añade después de generar el APK, para que la app se abra sin barra de dirección.
