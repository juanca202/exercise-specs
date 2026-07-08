# exercise-specs

Proyecto de ejemplo para la definición de historias de usuario y casos de prueba en el marco de una implementación **SDD (Spec-Driven Development)**.

## Propósito

Este repositorio sirve como laboratorio práctico para ejercitar el flujo completo de especificación de software:

- Especificación de Requisitos de Software (SRS)
- Historias de Usuario (US-XXX) y sus criterios de aceptación
- Casos de prueba (TC-XXX) derivados de esos criterios
- Trazabilidad entre requisitos, historias y pruebas

Este proyecto no gestiona Architecture Decision Records (ADRs).

## Cómo trabajar en este repositorio

Toda la definición y gestión del trabajo (historias de usuario, planificación, casos de prueba, trazabilidad, etc.) debe realizarse utilizando los **skills** del repositorio [juanca202/ai](https://github.com/juanca202/ai).

Antes de crear o modificar artefactos de especificación, consultar:

- [AGENTS.md](AGENTS.md) — reglas operativas y arquitectónicas del proyecto
- [.agents/MEMORY.md](.agents/MEMORY.md) — memoria persistente del proyecto

## Estructura

```
docs/
  requirements/   # Especificaciones de requisitos (SRS) por proyecto de ejemplo
  user-stories/   # Historias de usuario creadas a partir de los SRS
```
