# Arquitectura del Sistema Hospitalario

## Estilo seleccionado

Se propone un **monolito modular** para el backend. Cada módulo representa una capacidad del negocio y mantiene sus propias responsabilidades.

El frontend utiliza una arquitectura **basada en características**, donde cada módulo funcional contiene sus componentes, servicios de API, tipos, validaciones y hooks.

## Backend

El backend se divide en cuatro responsabilidades:

1. **Presentación:** controladores y contratos HTTP.
2. **Aplicación:** casos de uso y coordinación de operaciones.
3. **Dominio:** entidades, reglas y conceptos centrales.
4. **Infraestructura:** base de datos, servicios externos, mensajería y logging.

## Frontend

El frontend se divide en:

1. **App Router:** páginas, layouts y rutas.
2. **Features:** funcionalidades específicas.
3. **Shared:** componentes reutilizables.
4. **Core:** configuración, autenticación y cliente HTTP.

## Persistencia

Se propone PostgreSQL por su consistencia transaccional y adecuación para información clínica, financiera y administrativa.

## Integración

La comunicación frontend-backend se realizará mediante API REST sobre HTTPS.

## Escalabilidad

El monolito modular permite comenzar con una solución simple y separar módulos como microservicios en el futuro si el volumen o la complejidad lo requieren.
