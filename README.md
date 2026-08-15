# landingpage

Repositorio piloto para el flujo de Desarrollo operado por Hermes.

## Política inicial

- Desarrollo mediante issue, branch, worktree y pull request.
- Sin pushes directos a `main` después del commit de génesis autorizado.
- CI ejecutado en infraestructura self-hosted, sin runners cloud.
- Merge y deploy manuales durante el MVP.
- OpenSpec + Engram y receipt RDD obligatorios para los trabajos S/M/L.

## CI

El workflow inicial verifica únicamente la conexión y el aislamiento básico del runner local. Los gates de stack —format, lint, typecheck, tests, build y seguridad— se incorporarán con el bootstrap de la aplicación.
