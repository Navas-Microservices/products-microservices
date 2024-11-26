<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>


 # Product Microservices

 ## Dev
 1. Clonar el repositorio
 2. Instalar las dependencias
 3. Crear un archivo `.env` basado en el `.env.template`
 4.  Ejecutar migración de  prisma `npx prisma migrate dev`
 5. Levantar el servidor de Nats

```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats:latest
```
 6. Ejecutar `npm run start:dev`
    