# Sistema de Gestión de Tickets e Incidencias

Aplicación web Full Stack para la gestión y seguimiento de tickets e incidencias de soporte técnico.

El proyecto tiene como objetivo simular un sistema corporativo de gestión de incidentes, permitiendo registrar, consultar, actualizar y realizar seguimiento de solicitudes de soporte.

El proyecto está siendo desarrollado como portafolio profesional para demostrar buenas prácticas de desarrollo Full Stack, diseño de APIs REST, seguridad, testing, Docker y documentación.

## Estado del proyecto

🚧 En desarrollo

Actualmente se encuentra completada la configuración inicial del proyecto:

- Backend con Spring Boot.
- Frontend con Angular.
- Configuración inicial de testing.
- Estructura de repositorio Git.
- Flujo de trabajo basado en ramas y Conventional Commits.

Las funcionalidades de negocio serán implementadas progresivamente.

## Tecnologías

### Backend

- Java 25
- Spring Boot 4.1.1
- Spring Web MVC
- Maven
- JUnit
- Mockito

### Frontend

- Angular 22
- TypeScript
- Angular Router
- HTML
- CSS
- Vitest

### Próximamente

- PostgreSQL
- Spring Data JPA
- Spring Security
- JWT
- Docker
- Docker Compose

## Arquitectura

El proyecto está organizado como una aplicación Full Stack separando frontend y backend:

```text
Sistema de Gestión de Incidentes
│
├── backend/
│   └── Spring Boot REST API
│
├── frontend/
│   └── Angular SPA
│
└── README.md