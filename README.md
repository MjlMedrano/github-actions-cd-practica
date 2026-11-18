# github-actions-cd-practica

API REST CRUD de usuarios con Node.js y Express, contenerizada con Docker y desplegada automáticamente en AWS EC2 mediante un pipeline de CI/CD con GitHub Actions (build, push a Docker Hub, escaneo de vulnerabilidades y despliegue a staging y production).

## Endpoints

- GET /health
- GET /users
- GET /users/:id
- POST /users
- PUT /users/:id
- DELETE /users/:id

## URLs públicas

- Production: http://54.20.16.192/health
- Staging: http://54.20.16.192:8080/health

## Documentación del Laboratorio

Puedes encontrar el informe completo con capturas de pantalla y evidencias en el siguiente enlace:

- [Ver informe del laboratorio](./INFORME.md)
