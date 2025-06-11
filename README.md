# Mi Web Demo Surge

Este repositorio contiene una página web sencilla desplegada automáticamente en Surge.sh usando GitHub Actions.

## Despliegue automático

Cada vez que haces push a `main`, GitHub Actions despliega los cambios a Surge.

## Estructura del proyecto

- `index.html` — archivo principal
- `css/style.css` — estilos
- `js/app.js` — scripts
- `assets/` — recursos como imágenes

## Configuración

- Workflow en `.github/workflows/main.yml`
- Usa un token secreto `SURGE_TOKEN` configurado en GitHub Secrets
