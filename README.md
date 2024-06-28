# Proyecto Symfony 7 con Webpack Encore y TailwindCSS

## Descripción del Proyecto

Este proyecto es una aplicación web desarrollada utilizando Symfony 7, Webpack Encore y TailwindCSS. A continuación, se describe brevemente cada uno de estos componentes y su rol en el proyecto:

### Symfony 7

Symfony 7 es un framework de PHP para aplicaciones web y microservicios. Proporciona una estructura sólida y escalable que facilita el desarrollo y mantenimiento de aplicaciones web robustas. Symfony se destaca por su flexibilidad, reusabilidad de componentes y un ecosistema rico en funcionalidades. En este proyecto, Symfony 7 se utiliza para manejar el backend, la lógica de negocio, el enrutamiento, y la gestión de bases de datos.

### Webpack Encore

Webpack Encore es una herramienta de compilación moderna para JavaScript y otros activos front-end. Funciona como una abstracción sobre Webpack, simplificando la configuración y el uso de Webpack en proyectos Symfony. Encore permite la integración fácil de bibliotecas y herramientas de desarrollo, la optimización de activos y la generación de archivos de producción listos para ser desplegados. En este proyecto, Webpack Encore se encarga de compilar y gestionar los archivos JavaScript y CSS, asegurando una carga eficiente y rápida del sitio web.

### TailwindCSS

TailwindCSS es un framework de CSS utilitario que permite construir interfaces de usuario de manera rápida y eficiente mediante el uso de clases predefinidas. A diferencia de los frameworks tradicionales de CSS, TailwindCSS no proporciona componentes prediseñados, sino una serie de clases utilitarias que se pueden combinar para crear diseños personalizados. En este proyecto, TailwindCSS se utiliza para estilizar la interfaz de usuario, permitiendo un desarrollo ágil y flexible del frontend.

## Instrucciones de Instalación y Ejecución

### Requisitos Previos

Asegúrate de tener instalados los siguientes componentes en tu sistema:

- PHP 8.1 o superior
- Composer
- Node.js y npm

### Instalación

1. Clona este repositorio en tu máquina local:

    ```sh
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    cd nombre-del-repositorio
    ```

2. Instala las dependencias de PHP usando Composer:

    ```sh
    composer install
    ```

3. Instala las dependencias de JavaScript usando npm:

    ```sh
    npm install
    ```

### Configuración

1. Copia el archivo `.env` y renómbralo a `.env.local`:

    ```sh
    cp .env .env.local
    ```

2. Edita el archivo `.env.local` para configurar tu base de datos y otros parámetros necesarios.

### Compilar Activos Front-end

Para compilar los archivos CSS y JavaScript, utiliza Webpack Encore:

- Para desarrollo (con recarga en vivo):

    ```sh
    npm run dev
    ```

- Para producción (optimizado y minificado):

    ```sh
    npm run build
    ```

### Ejecutar el Servidor de Desarrollo

Para iniciar el servidor de desarrollo de Symfony, ejecuta:

```sh
symfony server:start -d
