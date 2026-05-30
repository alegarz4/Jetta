# Mi Jetta App

Bitacora personal para administrar mantenimiento, gasolina, gastos, fallas y diagnostico orientativo de un Volkswagen Jetta Clasico.

## Funciones

- Perfil del vehiculo con kilometraje actual.
- Alertas de servicios proximos o vencidos.
- Historial de servicios y fallas.
- Registro de cargas de gasolina.
- Calculo de rendimiento en km/L y costo por km.
- Registro de gastos por categoria.
- Diagnostico orientativo por sintomas.
- Diagnostico orientativo por sonido.
- Graficas de rendimiento, gastos mensuales y gastos por categoria.
- Resumen general del estado del vehiculo.
- Guardado automatico en el navegador.
- Exportacion e importacion de respaldo en JSON.
- Boton para actualizar la app cuando publiques cambios nuevos.
- Soporte basico para instalacion como app web.

## Como usar

Abre `index.html` en el navegador.

Los datos se guardan en el almacenamiento local del navegador. Si cambias de navegador, computadora o celular, exporta un respaldo desde el boton **Respaldar** e importalo en el nuevo dispositivo.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos los archivos de esta carpeta.
3. En GitHub, entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guarda los cambios.

GitHub generara una URL publica para abrir la app.

## Archivos principales

- `index.html`: aplicacion completa.
- `manifest.webmanifest`: configuracion para instalar como app.
- `service-worker.js`: cache basico para uso offline cuando se publica en web.
- `jetta-icon.svg`: icono de la app.
- `icon-192.png` y `icon-512.png`: iconos requeridos por navegadores moviles para instalacion.
- `docs/`: documentacion adicional.

## Privacidad

La app no envia datos a servidores. La informacion se queda en el navegador donde se usa. Si publicas este proyecto en GitHub, solo se publica el codigo de la app, no tus datos guardados.
