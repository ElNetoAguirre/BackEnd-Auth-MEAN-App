<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Backend para Auth MEAN App con Nest.

Éste **BackEnd** ha sido creado usando [NestJS](http://nestjs.com/), [Docker](https://www.docker.com/) y [MongoDB](https://www.mongodb.com), para servir como `Base de Datos` para el **FrontEnd**.

Cuenta con el CRUD completo y sus respectivas verificaciones para garantizar que la información que recibe del **FrontEnd** sea consistente con la información que requiere el **BackEnd**, tiene autenticación de ususarios mediante [JWT](https://jwt.io/), se peden crear ususarios para la parte privada y para la parte pública de manera independientes, maneja roles de ususario (administradores y públicos), etc.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Introducción a NestJS.
2. Introducción a Docker.
3. Conexión NestJS - Docker - MongoDB.
4. Variables de Entorno.
5. Modelos y Schemas.
6. DTO (Data Transfer Object).
7. Cración de Registros.
8. Generación de JWT (Jason Web Token).
9. Registro de Usuarios e Interfaces.
10. Protección de Rutas (@Guards).
11. Validación y obtención de usuarios.

# Backend en Nest

1. Clona el proyecto para extraer los datos del repositorio.

2. Ejecuta `npm install` para descargar e instalar los paquetes necesarios para la ejecución de la app.

3. Ejecutar `Docker Composer` mediante `docker composer up -d` para que permanezca ejecutandose.

4. Copiar el `.env.template`, renombrarlo a `.env` y llenar las variables de entorno.

5. Para ejecutar la aplicación en watch mode utiliza `npm run start:dev`.
