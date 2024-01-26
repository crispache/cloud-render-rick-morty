# Rick & Morty (Deploy app with Docker on Render)
Es un proyecto en el que se muestra un listado de los personajes de la serie Rick & Morty. En la interfaz, los usuarios pueden buscar personajes y acceder a los detalles de cada uno.

La API que se usa en el proyecto:
https://rickandmortyapi.com/


#### Tecnologías

- React
- Material UI
- TypeScript
- Vite
- Axios


#### Proceso

1. Fichero Dockerfile

![Fichero Dockerfile](./images/1-Dockerfile.png)


2. Crear Web Service en Render

![Crear Web Service en Render](./images/2-Create-web-service.png)


3.Proceso de creación del Web Service

![Crear Web Service](./images/3-creation-process.png)


4.Indicar el fichero Dockerfile

![Indicar fichero Dockerfile](./images/4-indicate-file-dockerfile.png)


5.Desplegando

![Desplegando](./images/5-building.png)


6.Despliegue con éxito

![Despliegue con éxito](./images/6-deployment-success.png)


## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install
```

## Development Server

Start the development server on `http://localhost:8080`:

```bash
# npm
npm run start

# pnpm
pnpm run start

# yarn
yarn start
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build
```
