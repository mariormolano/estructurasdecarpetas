# Guía de Estructura de Carpetas para Desarrollo

Esta guía proporciona una estructura de carpetas recomendada para proyectos de desarrollo, tanto para front-end como para back-end.

## Estructura General

proyecto/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── tests/
│   └── README.md
│
├── backend/
│   ├── src/
│   ├── tests/
│   └── README.md
│
├── docs/
├── .gitignore
└── README.md

## Estructura Front-end

backend/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   └── app.js
│
├── tests/
└── README.md


## Explicación de la Estructura

### Front-end

- `src/`: Contiene el código fuente de la aplicación.
  - `components/`: Componentes reutilizables.
  - `pages/`: Componentes de nivel superior que representan páginas.
  - `assets/`: Recursos estáticos como imágenes.
  - `styles/`: Archivos CSS o SCSS.
  - `utils/`: Funciones de utilidad y helpers.
- `public/`: Archivos públicos accesibles directamente.
- `tests/`: Pruebas unitarias y de integración.

### Back-end

- `src/`: Contiene el código fuente de la aplicación.
  - `controllers/`: Lógica de manejo de solicitudes.
  - `models/`: Definiciones de modelos de datos.
  - `routes/`: Definiciones de rutas de la API.
  - `services/`: Lógica de negocio.
  - `utils/`: Funciones de utilidad y helpers.
- `tests/`: Pruebas unitarias y de integración.

### Raíz del Proyecto

- `docs/`: Documentación adicional del proyecto.
- `.gitignore`: Especifica archivos y carpetas ignorados por Git.
- `README.md`: Documentación principal del proyecto.

## Buenas Prácticas

1. Mantén una estructura consistente en todos los proyectos.
2. Usa nombres descriptivos para carpetas y archivos.
3. Separa claramente el código front-end y back-end.
4. Incluye README.md en cada subdirectorio principal para explicar su propósito.
5. Mantén las pruebas cerca del código que están probando.
6. Utiliza un sistema de control de versiones como Git desde el inicio del proyecto.