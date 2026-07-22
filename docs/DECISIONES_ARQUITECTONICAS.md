# Decisiones Arquitectónicas

## ADR-001: Monorepo

Se utilizará un solo repositorio Git para mantener frontend, backend y documentación juntos.

## ADR-002: TypeScript

TypeScript será utilizado tanto en backend como en frontend para compartir conocimientos, tipos y convenciones.

## ADR-003: NestJS

NestJS organiza el backend mediante módulos, controladores, servicios, guards e inyección de dependencias.

## ADR-004: Next.js

Next.js permite estructurar el frontend por rutas, layouts y componentes reutilizables.

## ADR-005: PostgreSQL

PostgreSQL se propone para almacenar datos clínicos, administrativos, financieros y de auditoría.

## ADR-006: JWT y RBAC

JWT permite autenticar solicitudes. RBAC limita las acciones según los roles asignados.

## ADR-007: Auditoría

Las operaciones sensibles deben dejar registro del usuario, fecha, acción y recurso afectado.
