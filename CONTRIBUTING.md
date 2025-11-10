# Guía de Contribución

## Flujo de trabajo

- Trabajar con ramas por feature: `feat/<nombre-corto>`, `fix/<bug>`
- Abrir PRs hacia `main`, con template y referencia a Issue
- Requerir revisión de CODEOWNERS

## Estándar de commit (Conventional Commits)

- `feat: ...` nueva funcionalidad
- `fix: ...` corrección de bug
- `docs: ...` documentación
- `refactor: ...` refactor sin cambio funcional
- `chore: ...` tareas varias

## Calidad

- `pnpm lint`, `pnpm typecheck`, `pnpm build` deben pasar
- Acompañar features con tests (si hay framework de test)
