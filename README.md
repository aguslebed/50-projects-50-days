# Configuración Global de Tailwind CSS

Este proyecto ha sido configurado para usar Tailwind CSS v3 de manera local en todos los subdirectorios.

## 🚀 Cómo Empezar

### 1. Iniciar el Compilador (Watch Mode)
Para que Tailwind detecte tus cambios automáticamente y actualice los estilos, abre una terminal en la carpeta raíz (`1/`) y ejecuta:

```bash
npm run watch:css
```

**¡Mantén esta terminal abierta mientras trabajas!**

### 2. Usar en tus archivos HTML
En cualquier archivo HTML (por ejemplo, `Dia 6/index.html`), agrega el link al CSS compilado:

```html
<link rel="stylesheet" href="../dist/output.css">
```

*Nota: Ajusta la ruta `../` según la profundidad de tu carpeta.*

## 📁 Estructura

- `src/input.css`: Archivo fuente de Tailwind.
- `dist/output.css`: Archivo compilado (generado automáticamente).
- `tailwind.config.js`: Configuración que escanea todos los archivos `.html` y `.js` en todas las carpetas.

## 🛠 Comandos Disponibles

- `npm run build:css`: Compila el CSS una sola vez.
- `npm run watch:css`: Compila el CSS automáticamente cada vez que guardas un archivo.
