# Bruno Mars Página

Este proyecto es una página web dedicada a Bruno Mars. A continuación, se detallan las instrucciones para configurar y ejecutar el proyecto.

## Requisitos

- Node.js
- npm (Node Package Manager)

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/MarianoSagua/BrunoMarsPagina.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd BrunoMarsPagina
    ```
3. Instala las dependencias:
    ```sh
    npm install
    ```

## Scripts de npm

- `test`: Ejecuta el script de prueba (actualmente no especificado).
    ```sh
    npm run test
    ```
- `build-css`: Compila los archivos SCSS a CSS.
    ```sh
    npm run build-css
    ```
- `watch-css`: Observa los cambios en los archivos SCSS y ejecuta `build-css` automáticamente.
    ```sh
    npm run watch-css
    ```

## Estructura del Proyecto

- `scss/`: Directorio que contiene los archivos SCSS.
- `css/`: Directorio donde se generarán los archivos CSS compilados.
- `index.js`: Archivo principal del proyecto.

## Contribuir

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.