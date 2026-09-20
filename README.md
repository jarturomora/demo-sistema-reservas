# Demo: Sistema de reservas

Repositorio de demostración para el **Tema 3: Descubrimiento de producto y requisitos ágiles** de la asignatura **Procesos en Ingeniería del Software**.

El objetivo es mostrar, de forma sencilla, cómo organizar un backlog en GitHub y cómo representar distintos niveles de trabajo antes de llevar las historias a un tablero de tipo Scrum.

## Necesidad de usuario

> Los usuarios necesitan reservar una pista sin llamar por teléfono.

A partir de esta necesidad se organiza el trabajo en una jerarquía sencilla:

```text
Épica
└── Funcionalidad
    └── Historia de usuario
        └── Tarea técnica
```

## Estructura del backlog

### Épica

- [#1 Reservas online](https://github.com/jarturomora/demo-sistema-reservas/issues/1)

### Funcionalidades

- [#2 Consulta de disponibilidad](https://github.com/jarturomora/demo-sistema-reservas/issues/2)
- [#3 Creación y confirmación de reservas](https://github.com/jarturomora/demo-sistema-reservas/issues/3)

### Historias de usuario de “Consulta de disponibilidad”

- [#4 Consultar pistas disponibles por fecha](https://github.com/jarturomora/demo-sistema-reservas/issues/4) — 3 puntos
- [#5 Seleccionar fecha y hora para iniciar una reserva](https://github.com/jarturomora/demo-sistema-reservas/issues/5) — 2 puntos
- [#6 Informar cuando no existen horarios disponibles](https://github.com/jarturomora/demo-sistema-reservas/issues/6) — 2 puntos

### Tareas técnicas

#### Historia #4

- [#7 Crear endpoint para consultar disponibilidad](https://github.com/jarturomora/demo-sistema-reservas/issues/7)
- [#8 Mostrar horarios disponibles en la interfaz](https://github.com/jarturomora/demo-sistema-reservas/issues/8)

#### Historia #5

- [#9 Crear selector de fecha y hora](https://github.com/jarturomora/demo-sistema-reservas/issues/9)
- [#10 Validar que el horario continúa disponible](https://github.com/jarturomora/demo-sistema-reservas/issues/10)

#### Historia #6

- [#11 Gestionar respuesta sin disponibilidad](https://github.com/jarturomora/demo-sistema-reservas/issues/11)
- [#12 Mostrar mensaje informativo en la interfaz](https://github.com/jarturomora/demo-sistema-reservas/issues/12)

## Qué se mostrará en la demo

1. Cómo una necesidad se transforma en backlog.
2. Cómo una épica se divide en funcionalidades.
3. Cómo una funcionalidad se refina en historias de usuario.
4. Cómo una historia se concreta mediante criterios de aceptación y tareas técnicas.
5. Cómo las historias pueden estimarse con story points.
6. Cómo organizar después las historias en un tablero de trabajo con estados como:
   - Product Backlog
   - Ready
   - In Progress
   - In Review
   - Done

## Nota didáctica

La funcionalidad **Creación y confirmación de reservas** se deja deliberadamente sin descomponer en historias para mostrar que el backlog no tiene que estar completamente detallado desde el principio. El refinamiento es progresivo.

---

Este repositorio se utiliza únicamente con fines docentes.
