# MeteoChile (prototipo de app del clima de Chile)

🔗[github.com/sebasiohx/weather-frontend-m3](https://github.com/sebasiohx/weather-frontend-m3)

## 📘 Características

- ✅ Muestra el clima actual de Santiago y las otras capitales de las regiones de Chile
- ✅ Hecho con data falsa que simula la información del clima
- ✅ Desarrollado con Javascript para renderizar los datos en el DOM
- ✅ Hecho con Bootstrap para el diseño responsivo y SASS(scss)
- ✅ Uso de la metodología BEM para escribir los estilos CSS

## 🛠 Instalación

Sigue estos pasos para correr el proyecto localmente:

```bash
# 1. Clona el repositorio
git clone https://github.com/sebasiohx/weather-frontend-m3.git

# 2. Entra a la carpeta del proyecto
cd weather-frontend-m3

# 3. Abre el proyecto (sin dependencias, es vanilla JS)
# Opción A: Abre index.html directo en el navegador
# Opción B: Usa Live Server en VS Code
```

> ⚠️ **Requisitos previos:** Solo necesitas un navegador moderno. No se requiere Node.js ni npm.

## 📁 Estructura del proyecto

```
WEATHER-FRONTEND-M3/
├── assets/
│   ├── css/
│   │   ├── styles.css             *estilos compilados
│   │   └── styles.css.map
│   ├── img/                       *imágenes del sitio
│   ├── js/
│   │   └── main.js                *funcionalidades del sitio
│   └── scss/
│       ├── abstracts/             *variables, funciones y mixins
│       │   ├── _functions.scss
│       │   ├── _index.scss
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base/                  *estilos base del sitio
│       │   ├── _base.scss
│       │   ├── _index.scss
│       │   └── _reset.scss
│       ├── components/            *estilos de los componentes visuales
│       │   ├── _forecast.scss
│       │   ├── _hero-card.scss
│       │   ├── _index.scss
│       │   └── _regions-card.scss
│       ├── layout/                *estilos estructuras base
│       │   ├── _footer.scss
│       │   └── _index.scss
│       ├── pages/                 *estilos de paginas específicas
│       │   ├── _detail.scss
│       │   ├── _home.scss
│       │   └── _index.scss
│       ├── themes/                *estilos de tema de color
│       ├── vendors/               *estilos de recursos externos
│       └── styles.scss            *archivo índice de estilos
├── .gitignore
├── index.html
└── README.md
```

## 🧰 Tecnologías

| Tecnología | Versión | Uso                   |
| ---------- | ------- | --------------------- |
| HTML       | 5       | Estructura de la app  |
| CSS        | BEM     | Metodología de clases |
| SASS       | SCSS    | Estilos y animaciones |
| JavaScript | ES2024  | Lógica del frontend   |

---
