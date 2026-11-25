# SkinMarket Pro Backend

Servicios Spring Boot para autenticación y usuarios, productos, pedidos y postulaciones a vendedor. Usa Java 21 y MySQL 8.4.

1. Crea `.env` a partir de `.env.example` y establece credenciales y secretos propios.
2. Ejecuta `docker compose up -d --build`.
3. Consulta la API en `http://localhost:8080/api/v1` y las interfaces Swagger en `/api/v1/{usuarios,productos,pedidos}/swagger-ui.html`.

Para ejecutar pruebas con Java 21, abre la carpeta `backend` y ejecuta `./mvnw test` o `mvnw.cmd test` en Windows.

La [arquitectura](docs/Arquitectura_API.md), la [planilla de endpoints](docs/Documentacion_APIs.xlsx), Postman y el respaldo SQL están incluidos. La interfaz React está en [SkinMarket](https://github.com/NevanXll/SkinMarket).
