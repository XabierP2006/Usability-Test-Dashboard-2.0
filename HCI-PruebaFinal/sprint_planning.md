# Sprint Planning — Usability Test Dashboard 2.0

## 1. Información del Sprint

| Elemento | Detalle |
| :--- | :--- |
| **Sprint ID** | Sprint 01 — Optimización de Interfaz y Navegación |
| **Duración** | 2 Horas (Prueba Práctica Final) |
| **Scrum Master / Dev** | Xabier Perez |
| **Estado** | En curso |

---

## 2. Objetivo del Sprint (Sprint Goal)
Optimizar la experiencia de usuario (UX) del Dashboard mediante la simplificación de la navegación principal, la aplicación de jerarquía visual clara y la estandarización de la arquitectura de información, asegurando que el sistema sea intuitivo y eficiente para la gestión de pruebas de usabilidad.

---

## 3. Sprint Backlog (Historias de Usuario Seleccionadas)

Se han seleccionado las siguientes historias del Product Backlog para ser completadas en este Sprint, priorizando aquellas que impactan directamente en la navegación y visualización del sistema:

| ID | Título | Prioridad | Estimación |
| :--- | :--- | :--- | :--- |
| **HU-01** | Rediseño de la Barra de Navegación Principal | Alta | 5 SP |
| **HU-04.1** | Mejora de la Visualización en el Dashboard | Media | 3 SP |
| **HU-08** | Documentación Técnica y UX | Alta | 2 SP |

---

## 4. Desglose de Tareas (Basado en Mejoras de Desarrollo)

Para alcanzar el objetivo, se ejecutarán las siguientes tareas técnicas basadas en los principios de HCI:

| Tarea | Descripción | Vincualción HCI / UX |
| :--- | :--- | :--- |
| **T1. Simplificación** | Reducir el número de botones visibles en la Navbar y usar menús desplegables. | Ley de Hick (Reducción de opciones). |
| **T2. Jerarquía** | Destacar la acción "Nuevo Test" con color primario y estilo sólido. | Jerarquía Visual y Enfoque de Atención. |
| **T3. Espacio** | Ajustar márgenes internos y dimensiones de la barra superior. | Uso de Espacio en Blanco (Gestalt). |
| **T4. Iconografía** | Implementar un set de iconos minimalistas y consistentes (Boxicons). | Heurística #4: Consistencia y Estándares. |
| **T5. Zonificación** | Agrupar funciones en bloques lógicos (Gestión, Usuario, Sistema). | Heurística #2: Relación Sistema-Mundo Real. |

---

## 5. Capacidad y Disponibilidad
*   **Desarrollador:** Xabier Perez (100% de disponibilidad durante el Sprint).
*   **Herramientas:** React, Next.js, CSS Modules, Git/GitHub.

---

## 6. Definition of Done (DoD)
Para que una tarea se considere terminada, debe cumplir:
1.  **Funcionalidad:** El código compila y la navegación es operativa.
2.  **HCI Compliance:** La interfaz sigue los principios de jerarquía y minimalismo.
3.  **Responsividad:** La barra de navegación es funcional en resoluciones de Tablet y Desktop.
4.  **Código:** No existen advertencias críticas de linting.
5.  **Evidencia:** Se ha realizado el commit correspondiente en el repositorio.

---

## 7. Estrategia de Evidencia (Commits Planificados)

Se realizarán commits incrementales para evidenciar el proceso de rediseño:
1.  `feat(nav): simplify buttons and implement dropdowns for secondary functions`
2.  `ui(nav): establish visual hierarchy for primary action 'Nuevo Test'`
3.  `style(layout): optimize spacing and reduce navbar vertical density`
4.  `ui(ux): implement consistent minimalist iconography set`
5.  `refactor(nav): logically group functions into management and user blocks`

--- 
