# React: Zero to Expert — Mastery Roadmap

> Roadmap completo para dominar React desde cero hasta aplicaciones fullstack con el stack MERN.

---

## Tabla de Contenidos

- [Fase 1 — Fundamentos](#fase-1--fundamentos)
  - [Sección 1 — Introducción](#sección-1--introducción)
  - [Sección 2 — Introducción a React y conceptos generales](#sección-2--introducción-a-react-y-conceptos-generales)
  - [Sección 3 — Reforzamiento JavaScript / TypeScript](#sección-3--reforzamiento-javascript--typescript)
  - [Sección 4 — Primeros pasos en React](#sección-4--primeros-pasos-en-react)
  - [Sección 5 — Pruebas automáticas: Unit Testing](#sección-5--pruebas-automáticas-unit-testing)
- [Fase 2 — Aplicaciones Core con React](#fase-2--aplicaciones-core-con-react)
  - [Sección 6 — GifExpertApp](#sección-6--gifexpertapp)
  - [Sección 7 — Optimización y despliegue](#sección-7--optimización-y-despliegue)
  - [Sección 8 — Testing: Pruebas sobre GifsApp](#sección-8--testing-pruebas-sobre-gifsapp)
  - [Sección 9 — Profundizando Hooks y React](#sección-9--profundizando-hooks-y-react)
  - [Sección 10 — Profundizando Hooks: useReducer](#sección-10--profundizando-hooks-usereducer)
  - [Sección 11 — Memorización y optimizaciones](#sección-11--memorización-y-optimizaciones)
  - [Sección 12 — useContext](#sección-12--usecontext)
- [Fase 3 — SPAs y Arquitectura Avanzada](#fase-3--spas-y-arquitectura-avanzada)
  - [Sección 13 — Single Page Application (SPA)](#sección-13--single-page-application-spa)
  - [Sección 14 — Funcionalidad, caché y optimizaciones](#sección-14--funcionalidad-caché-y-optimizaciones)
  - [Sección 15 — Context API: Búsquedas y favoritos](#sección-15--context-api-búsquedas-y-favoritos)
  - [Sección 16 — Testing HeroesApp](#sección-16--testing-heroesapp)
  - [Sección 17 — Desplegar aplicación](#sección-17--desplegar-aplicación)
  - [Sección 18 — Panel administrativo de productos](#sección-18--panel-administrativo-de-productos)
  - [Sección 19 — Productos y Backend](#sección-19--productos-y-backend)
  - [Sección 20 — Auth](#sección-20--auth)
  - [Sección 21 — Formularios y productos](#sección-21--formularios-y-productos)
  - [Sección 22 — Carga de archivos](#sección-22--carga-de-archivos)
  - [Sección 23 — Punto de control](#sección-23--punto-de-control)
- [Fase 4 — MERN Stack Full-Stack](#fase-4--mern-stack-full-stack)
  - [Sección 24 — MERN Calendar: Estructura y Diseño](#sección-24--mern-calendar-estructura-y-diseño)
  - [Sección 25 — CalendarApp Backend: Node, Express, Mongo](#sección-25--calendarapp-backend-node-express-mongo)
  - [Sección 26 — Backend: Eventos del calendario CRUD](#sección-26--backend-eventos-del-calendario-crud)
  - [Sección 27 — Desplegar el backend a la nube](#sección-27--desplegar-el-backend-a-la-nube)
  - [Sección 28 — MERN: Calendario + Backend](#sección-28--mern-calendario--backend)
  - [Sección 29 — MERN CRUD: Eventos del calendario](#sección-29--mern-crud-eventos-del-calendario)
  - [Sección 30 — Fin del MERN: Despliegue a producción](#sección-30--fin-del-mern-despliegue-a-producción)

---

## Fase 1 — Fundamentos

### Sección 1 — Introducción

Presentación general del curso y la metodología de aprendizaje.

---

### Sección 2 — Introducción a React y conceptos generales

Dos presentaciones introductorias sobre:

- ¿Qué es React?
- Puntos clave sobre React

> Se recomienda avanzar con calma si es el primer contacto con React. Todo comienza con un "Hola Mundo".

---

### Sección 3 — Reforzamiento JavaScript / TypeScript

`react-ts-bases`

Conceptos de JavaScript moderno y TypeScript necesarios antes de entrar a React:

| Tema | Descripción |
|------|-------------|
| `const`, `let`, `var` | Uso correcto de declaraciones de variables |
| Template strings | Interpolación de texto |
| Interfaces | Definición y uso en TypeScript |
| Arreglos | Recorrerlos y manipularlos |
| Funciones | Simples, complejas y con múltiples retornos |
| Desestructuración | Objetos y arreglos |
| Enums | Valores constantes tipados |
| Módulos | Importar y exportar |
| Promesas | Manejo de asincronía |
| Fetch API | Peticiones HTTP |
| Giphy API | Consumo de API externa |
| `async` / `await` | Código asincrónico limpio |
| Buenas prácticas | Optimización y clean code |

---

### Sección 4 — Primeros pasos en React

`react-first-steps`

Fundamentos esenciales de React para construir la base del conocimiento:

- Componentes: estructura y nomenclatura
- Hook `useState`
- CSS condicional y módulos CSS
- Impresión de variables en JSX
- Props
- Y mucho más

---

### Sección 5 — Pruebas automáticas: Unit Testing

`react-first-steps`

Introducción al testing en el ecosistema React:

| Herramienta / Concepto | Descripción |
|------------------------|-------------|
| Vitest + Vitest UI | Framework de testing |
| Índice de cobertura | Medir qué tanto se prueba |
| `describe` y `test` | Organización de pruebas |
| Espías | Verificar llamadas a funciones |
| Mocks | Simular módulos y componentes |
| Snapshots | Pruebas de regresión visual |
| Debugging en consola | Diagnóstico durante pruebas |
| Testing Library | Integración con React |

---

## Fase 2 — Aplicaciones Core con React

### Sección 6 — GifExpertApp

Aplicación práctica que cubre:

- Peticiones HTTP
- Debounce
- Manejo de estado
- Comunicación entre componentes
- `useEffect`
- Variables de entorno
- Fuentes personalizadas

---

### Sección 7 — Optimización y despliegue

- Custom Hooks (hooks personalizados)
- React DevTools
- `useRef`
- Generar versión de producción
- Separación de responsabilidades

---

### Sección 8 — Testing: Pruebas sobre GifsApp

`react-ts-gifs`

- Pruebas sobre hooks y custom hooks
- Tareas asíncronas y timeouts
- Pruebas sobre `axios`
- Integrar testing en el proceso de build
- Espías y sobreescritura de funciones
- Manejo de excepciones

---

### Sección 9 — Profundizando Hooks y React

Hooks del core de React y patrones avanzados:

- `useState`, `useRef`, `useEffect`
- Custom Hooks: `useCounter`, `usePokemon`, `useTrafficLight`
- Conectar múltiples custom hooks entre sí

---

### Sección 10 — Profundizando Hooks: useReducer

- Patrón Reducer
- Hook `useReducer`
- Validadores de esquemas con **Zod**
- Efectos sobre estados
- `localStorage` y `sessionStorage`
- Condiciones en reducers

---

### Sección 11 — Memorización y optimizaciones

Hooks y APIs de optimización en React:

| API / Hook | Uso |
|------------|-----|
| `useMemo` | Memorizar valores costosos |
| `useCallback` | Memorizar funciones |
| `useOptimistic` | Actualizaciones optimistas en pantalla |
| `useTransition` | Evitar bloqueos de UI |
| `use` API | Nueva API de React |
| `Suspense` | Carga diferida de componentes |

---

### Sección 12 — useContext

`react-ts-hooks-app`

- Hook `useContext` y nueva API `use`
- Persistencia de sesiones de usuario
- Rutas de la aplicación
- Rutas privadas y públicas
- Diseño condicional

---

## Fase 3 — SPAs y Arquitectura Avanzada

### Sección 13 — Single Page Application (SPA)

Construcción de aplicaciones de una sola página con React.

---

### Sección 14 — Funcionalidad, caché y optimizaciones

Estrategias de caché y optimización en aplicaciones React.

---

### Sección 15 — Context API: Búsquedas y favoritos

Uso avanzado del Context API para búsquedas y gestión de favoritos.

---

### Sección 16 — Testing HeroesApp

Pruebas automatizadas sobre la aplicación de héroes.

---

### Sección 17 — Desplegar aplicación

`ReactSPAHeroes_` / `react-ts-heroes-app`

Despliegue de la SPA a producción.

---

### Sección 18 — Panel administrativo de productos

- Rutas y `QueryParameters`
- Persistencia sin estado
- Navegación
- Fuentes personalizadas (Google Fonts + Tailwind)
- Transformar código generado por AI al proyecto

---

### Sección 19 — Productos y Backend

- **TanStack Query**: `QueryParams`, `QueryKeys`
- Paginación
- Transformaciones de argumentos

---

### Sección 20 — Auth

`react-ts-telslo-shop`

- TanStack con **Zustand**
- Zustand como gestor de estado global
- Generalidades de los JWTs
- Mantener la sesión del usuario
- Autenticación y autorización
- Protección de rutas

---

### Sección 21 — Formularios y productos

`teslo-shop-react`

Manejo avanzado de formularios y CRUD de productos.

---

### Sección 22 — Carga de archivos

`teslo-shop-react`

Upload de archivos desde el frontend React.

---

### Sección 23 — Punto de control

Revisión y consolidación de los conocimientos adquiridos hasta este punto.

---

## Fase 4 — MERN Stack Full-Stack

### Sección 24 — MERN Calendar: Estructura y Diseño

`react-mern-calendar`

- Diseño y estructura de la aplicación de calendario
- Componentes de terceros y Modals
- Configuración de **Redux**
- CRUD local
- **MomentJS** para manejo de fechas

---

### Sección 25 — CalendarApp Backend: Node, Express, Mongo

`MERN-Calendar-Backend`

| Tecnología | Uso |
|------------|-----|
| Node.js | Runtime del servidor |
| Express | Framework HTTP |
| Mongoose | ODM para MongoDB |
| JWT | Autenticación stateless |
| CORS | Configuración de acceso |
| MongoDB + MongoAtlas | Base de datos en la nube |
| MongoCompass | GUI para MongoDB |

---

### Sección 26 — Backend: Eventos del calendario CRUD

`MERN-Calendar-Backend`

- CRUD completo de eventos de calendario
- Modelos, validaciones automáticas y personalizadas

---

### Sección 27 — Desplegar el backend a la nube

- Configuración de **Railway**
- Subida a GitHub
- Variables de entorno en producción
- Prueba del backend en la nube

---

### Sección 28 — MERN: Calendario + Backend

Conexión del backend con el frontend React.

`react-mern-calendar` + `MERN-Calendar-Backend`

---

### Sección 29 — MERN CRUD: Eventos del calendario

`react-mern-calendar`

Persistencia de eventos del calendario usando el backend: acciones asíncronas que ejecutan las acciones síncronas del store de Redux.

---

### Sección 30 — Fin del MERN: Despliegue a producción

Despliegue completo de la aplicación fullstack:

1. Build de producción
2. Desplegar cambios a Railway
3. Variables de entorno en React
4. Manejo de todas las rutas desde el backend
