# primer-repo-devOps
# Evaluacion 1 - Proyecto

## Convenciones de commits
`feat:` para nuevas funcionalidades (ej. feat: agrega login)
`fix:` para corrección de errores (ej. fix: corrige formato)
`docs:` para cambios en la documentación (ej. docs: actualiza README)

## Naming de ramas
`main` → producción (código estable)
`develop` → rama de integración
`feature/*` → para trabajar en nuevas funciones
`hotfix/*` → para correcciones urgentes

## Flujo de merges (GitFlow)
Las ramas `feature/` se unen hacia `develop` mediante un Pull Request.
Las ramas `hotfix/` se unen hacia `main` mediante un Pull Request.
**NUNCA** se trabaja directo en `main`.

## Estrategias de revisión
Todos los cambios deben integrarse a través de Pull Requests (PR) para revisar el código antes de hacer merge, validar que funcione y mantener la calidad.
