# Software Development Agents

Colección de agentes especializados para apoyar distintas fases del desarrollo de software: análisis, diseño, implementación, depuración, calidad y aspectos de plataforma. Cada agente está descrito en un archivo Markdown y puede consultarse como guía de trabajo para un asistente de IA.

## Agentes disponibles

### Análisis (`agents/analysis/`)

- [`business-analyst.md`](agents/analysis/business-analyst.md): análisis de necesidades y requisitos de negocio.
- [`codebase-analyst.md`](agents/analysis/codebase-analyst.md): exploración y comprensión de una base de código existente.
- [`software-architect.md`](agents/analysis/software-architect.md): arquitectura y decisiones de diseño de software.

### Depuración (`agents/debugging/`)

- [`bug-investigator.md`](agents/debugging/bug-investigator.md): investigación de errores y comportamientos inesperados.
- [`root-cause-analyst.md`](agents/debugging/root-cause-analyst.md): análisis de causa raíz.

### Desarrollo (`agents/development/`)

- [`dotnet-specialist.md`](agents/development/dotnet-specialist.md): desarrollo con tecnologías .NET.
- [`react-specialist.md`](agents/development/react-specialist.md): desarrollo con React.
- [`sql-server-specialist.md`](agents/development/sql-server-specialist.md): trabajo especializado con SQL Server.

### Orquestación (`agents/orchestration/`)

- [`orchestrator.md`](agents/orchestration/orchestrator.md): coordinación del trabajo entre agentes especializados.

### Plataforma (`agents/platform/`)

- [`performance-engineer.md`](agents/platform/performance-engineer.md): análisis y mejora del rendimiento.
- [`security-engineer.md`](agents/platform/security-engineer.md): revisión de aspectos de seguridad.

### Calidad (`agents/quality/`)

- [`code-reviewer.md`](agents/quality/code-reviewer.md): revisión de cambios de código.
- [`qa-engineer.md`](agents/quality/qa-engineer.md): planificación y trabajo de aseguramiento de calidad.

## Cómo utilizar los agentes

1. Identifica la tarea que quieres resolver y el área correspondiente.
2. Abre el archivo Markdown del agente adecuado y proporciona su contenido como instrucciones o contexto a tu asistente de IA.
3. Comparte también los requisitos, el código relevante y las restricciones del proyecto.
4. Para tareas que involucren varias disciplinas, consulta `agents/orchestration/orchestrator.md` para orientar la coordinación.
5. Revisa y valida siempre las propuestas antes de incorporarlas al proyecto.

Los agentes son guías de trabajo; adapta sus recomendaciones al contexto, las convenciones y los requisitos de tu proyecto.

## Estructura del repositorio

```text
agents/
├── analysis/
├── debugging/
├── development/
├── orchestration/
├── platform/
└── quality/
```

## Contribuir

Las mejoras y nuevos agentes son bienvenidos. Para contribuir, añade o actualiza un archivo Markdown en la categoría adecuada y procura que su propósito y ámbito queden claros. Antes de proponer un cambio, comprueba que las instrucciones sean concretas, útiles y coherentes con el resto de la colección.

## Licencia

Actualmente no se especifica una licencia en este repositorio. Si quieres permitir y definir formalmente la reutilización del contenido, añade un archivo `LICENSE` con la licencia elegida.
