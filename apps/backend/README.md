# Backend — NestJS

El backend está organizado como un monolito modular.

## Capas por módulo

- `presentation`: controladores y DTO de entrada.
- `application`: casos de uso y servicios de aplicación.
- `domain`: entidades, interfaces y reglas del negocio.
- `infrastructure`: persistencia y adaptadores externos.

## Directorios globales

- `config`: configuración.
- `common`: elementos reutilizables.
- `infrastructure`: base de datos, logging y servicios compartidos.
- `modules`: módulos funcionales.
- `test`: pruebas futuras.

Los archivos TypeScript están vacíos porque esta entrega define únicamente la arquitectura.
