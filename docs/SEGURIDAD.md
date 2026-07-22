# Seguridad propuesta

## Autenticación

- Inicio de sesión mediante usuario y contraseña.
- Emisión de token JWT.
- Renovación y expiración controlada.

## Autorización

- Control de acceso basado en roles.
- Validación de permisos en el backend.
- Protección de rutas en el frontend.

## Protección de datos

- Uso de HTTPS.
- Contraseñas almacenadas con hash seguro.
- Validación de entradas.
- Registro de operaciones sensibles.
- Separación de información clínica y administrativa.

## Auditoría

Cada evento sensible debería almacenar:

- Usuario
- Fecha y hora
- Acción
- Recurso
- Identificador del registro
- Resultado de la operación
