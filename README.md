# CarrenoRangel-post1-u12

Contenerizacion con Docker (multi-stage), Docker Compose y despliegue en Railway.

## Construir imagen
docker build -t catalogo-app:local .

## Ejecutar con Docker Compose
docker compose up -d --build

## Verificar salud
curl http://localhost:8080/actuator/health

## Railway
- Conectar el repo en railway.app
- Agregar PostgreSQL y variables de entorno
- Generar dominio publico
- Verificar /actuator/health y endpoints REST

## Evidencias
Coloca las capturas en img/:
- img/checkpoint1-docker-build.png
- img/checkpoint2-compose-health.png
- img/checkpoint3-railway-endpoints.png
