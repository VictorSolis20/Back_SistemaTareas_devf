# Backend para Sistema de Tareas con Node.js y MongoDB

Este proyecto es un sistema de gestión de tareas que permite a los usuarios crear tareas con descripciones personalizadas. El backend está desarrollado en Node.js y se conecta a una base de datos de MongoDB, utilizando autenticación de usuarios mediante JWT (JSON Web Tokens).

## Características Principales

- **Colecciones en la Base de Datos:**
  - Usuarios: Almacena la información de los usuarios registrados en el sistema.
  - Tareas: Almacena las tareas creadas por los usuarios.

- **Estructura del Proyecto:**
  - Rutas: Definimos las rutas que manejan las peticiones HTTP.
  - Modelos: Definimos los modelos de datos para usuarios y tareas.
  - Middlewares: Implementamos middlewares para la autenticación y validación.
  - Controladores: Controladores para manejar las operaciones CRUD en usuarios y tareas.
  - Variables de Entorno: Utilizamos variables de entorno para configurar aspectos sensibles del proyecto.

- **Protección con JWT:**
  - Utilizamos JSON Web Tokens (JWT) para proteger los endpoints.
  - Cada usuario autenticado recibe un token que debe incluir en las solicitudes para acceder a las funciones protegidas.

## Requisitos y Configuración

Antes de ejecutar el proyecto, asegúrate de configurar las variables de entorno adecuadas, como las credenciales de MongoDB y las claves secretas de JWT.

## Instalación y Uso

1. Clona este repositorio.
2. Instala las dependencias utilizando `npm install`.
3. Configura las variables de entorno en un archivo `.env`.
4. Inicia el servidor con `npm run server`.
