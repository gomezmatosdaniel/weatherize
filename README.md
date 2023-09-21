# Weatherize

## [👉🏽Live demo](https://weatherizeastro.netlify.app/)

> **Pequeña aplicación del tiempo para probar bun y Astro a la vez**
![image](https://github.com/gomezmatosdaniel/weatherize/assets/65901016/b01fa500-4719-41f2-87b4-1f3807fc56a0)

## Instalación del Proyecto

> Yo uso bun para instalar la app

| Comandos                     | Resultado             |
| -----------------------      |:---------------------:|
| `bun install`                | Instalar dependencias |
| `bun --bun astro dev`        | Inicializa el servidor local de desarrollo en  `localhost:4321`|
| `bun --bun astro build`      | Construye tu sitio utilizando Bun como el entorno de ejecución |

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
│   │   └── WeatherCard.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│   │    └── index.astro
│   └── api/
│        └── api.js
└── package.json
```
