# **Back3EntregaFinal**

### Este es un proyecto de backend para gestionar usuarios, mascotas, adopciones y sesiones utilizando Node.js, Express, MongoDB, y herramientas relacionadas. También incluye pruebas automatizadas y simulaciones de datos ficticios.

Contenido del Proyecto
Estructura del Proyecto
src/: Contiene el código fuente del backend.

## 🧨🧨Vínculo a Docker Hub: https://hub.docker.com/u/leacodex🧨🧨

### routes/: Define las rutas de la API para usuarios, mascotas, adopciones, sesiones, y datos ficticios.
### controllers/: Implementa la lógica de negocio para las diferentes entidades.
models/: Define los modelos de MongoDB para usuarios, mascotas y adopciones.
services/: Contiene los servicios para interactuar con la base de datos.
mocks/: Genera datos ficticios para pruebas y simulaciones.
app.js: Configura la aplicación Express.
server.js: Inicia el servidor.
test/: Contiene pruebas automatizadas utilizando Mocha, Chai, y chai-http.
adoption.router.test.js: Pruebas para las rutas relacionadas con adopciones.

## Características Principales

Gestión de Usuarios: CRUD para usuarios.
Gestión de Mascotas: CRUD para mascotas con soporte para estados de adopción.
Gestión de Adopciones: Vincula usuarios y mascotas con funcionalidad para registrar adopciones.
Simulaciones de Datos: Generación de datos ficticios para pruebas con faker.
Documentación Interactiva: Utiliza Swagger para exponer una interfaz interactiva de API.
Pruebas Automatizadas: Verifica el correcto funcionamiento de las rutas y funcionalidades clave.
Requisitos
Node.js (versión recomendada: 16.x o 18.x)
MongoDB (local o Atlas)
NPM o Yarn
