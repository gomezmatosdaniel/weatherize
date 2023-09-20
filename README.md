# Weatherize

[![Open in Netlify](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/Netlify_logo.svg/1200px-Netlify_logo.svg.png)](https://weatherizeastro.netlify.app/)

> **Pequeña aplicación del tiempo para probar bun y Astro a la vez** 


## Instalación del Protecto

> Yo uso bun para instalar la app

| Comandos                   | Resultado             |
| -----------------------    |:---------------------:|
| bun install                | Instalar dependencias |
| bun --bun astro dev        | Inicializa el servidor local de desarrollo en  `localhost:4321`|
| bun --bun astro build      | Construye tu sitio utilizando Bun como el entorno de ejecución |

## Estructura del Proyecto

```text
/
├── public/
│   └── favicon.svg
│   └── assets/
│        └── imgs* 
├── src/
│   ├── components/
│   │   └── Home.astro
    │   └── WeatherCard.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│   │    └── index.astro
│   └── api/
│        └── api.js
└── package.json
```
