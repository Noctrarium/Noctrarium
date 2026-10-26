# Noctrarium — versión limpia

Proyecto estático (HTML, CSS y JavaScript), sin Node, compilación ni dependencias. Diseñado para subir directamente a la raíz del repositorio `Noctrarium` y publicarse en GitHub Pages.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Sube **el contenido** de la carpeta `Noctrarium-clean` a la raíz del repositorio (debe quedar `index.html` en la raíz, no dentro de otra carpeta).
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera unos minutos y abre `https://cautisticpack.github.io/Noctrarium/`.

Esta versión no usa Vite, por lo que no necesita `npm install`, un workflow ni configurar una ruta `base`.

## Funciones
- Diseño adaptable a móvil y escritorio.
- Conexión opcional con una wallet EVM inyectada.
- Detecta la red Base y permite solicitar el cambio de red.
- Consulta el saldo ERC-20 usando una llamada RPC pública de solo lectura.
- Módulos visuales para swap y NFT, aún sin integración transaccional.
- Arcade de demostración con puntos ficticios locales, sin apuestas, tokens ni premios reales.

## Seguridad
Nunca introduzcas aquí una frase semilla o una clave privada. Esta página no las solicita. Revisa la dirección del contrato y la red antes de confiar en cualquier dato. La integración de swap y la galería NFT no están activadas.
