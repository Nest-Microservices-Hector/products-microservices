# Product Microservice

## Dev

1. Conar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `.env.template`
4. Ejecutar migracion de de prixma `npx prisma migrate dev`
5. Levantar el servidor de nats
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar `npm run start:dev`