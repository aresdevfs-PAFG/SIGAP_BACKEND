# SIGAP Backend

Backend nuevo de SIGAP para seguimiento modular de proyectos e investigaciones. Este repositorio inicia una implementación separada del legado PHP de `MOCKUP/`.

## Stack inicial

- Java 17
- Spring Boot 4.1.2
- Spring MVC como API REST
- Maven
- MySQL se integrará en una etapa posterior mediante migraciones versionadas

## Ejecutar localmente

Requiere JDK 17 y Maven 3.6.3 o posterior.

```powershell
mvn spring-boot:run
```

El backend usa el puerto `8081` para convivir con el XAMPP del legado en `8080`.

- `GET http://localhost:8081/api/v1/status`

La respuesta inicial confirma que la API está arriba. Aún no hay conexión a base de datos ni funcionalidades de negocio.

## Documentación

La arquitectura, actores y modelo de dominio inicial están en [`docs/SIGAP_Remake/`](docs/SIGAP_Remake/).
