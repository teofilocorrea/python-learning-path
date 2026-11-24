# Python Learning Path

Ruta de Python aplicado a datos: de fundamentos a ETL, testing y métricas de gestión. Hub de proyectos de un PM técnico.

## Por qué existe este proyecto

Lidero proyectos de tecnología y quiero tomar decisiones con datos en lugar de especular. Para eso necesito entender cómo se construye y se mantiene un producto de datos de punta a punta. Cada fase de esta ruta es un proyecto real, con su repositorio, sus tickets en Jira, su control de cambios en GitHub y su documentación de cierre.

## Cómo está organizada la ruta

| Fase | Proyecto | Foco técnico | Foco de gestión (GitHub) | Estado |
|------|----------|--------------|--------------------------|--------|
| 0 | Hub y fundamentos de GitHub | Repositorio, estructura | Ramas, Pull Requests | En curso |
| 1 | Fundamentos de Python | Tipos, control de flujo | Issues | Pendiente |
| 2 | Funciones y OOP | Funciones, clases | Milestones | Pendiente |
| 3 | pandas | Limpieza y análisis | Projects | Pendiente |
| 4 | Python + PostgreSQL | ETL | Releases y tags | Pendiente |
| 5 | Testing + CI | pytest, GitHub Actions | Protección de main | Pendiente |
| 6 | API de Jira y métricas | Datos de gestión | Integración GitHub-Jira | Pendiente |

## Estructura de cada proyecto

    asset/        Recursos visuales
    dataset/      Datos de entrada
    docs/         Documentación y cierre (project_closure.md)
    src/          Código fuente
    tests/        Pruebas
    requirements.txt
    README.md

## Forma de trabajo

- Una rama por ticket, con la clave de Jira: `feature/PYL-12-leer-csv`
- Commits convencionales: `feat:`, `fix:`, `docs:`
- Todo cambio entra a `main` mediante Pull Request

## Autor

Teófilo Correa Rojas, Project Manager Digital | Data analytics
