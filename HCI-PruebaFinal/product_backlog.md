# Product Backlog — Usability Test Dashboard 2.0

## Visión del Producto
Plataforma institucional para gestionar pruebas de usabilidad, permitiendo registrar tareas, observaciones, sesiones de testeo, indicadores de usabilidad, hallazgos y mejoras sugeridas, con el objetivo de mejorar la experiencia del usuario final.

---

## Épicas

| Épica | Descripción | Prioridad |
|-------|-------------|----------|
| E-01 | Módulo de Gestión de Tareas | Alta |
| E-02 | Módulo de Observaciones | Alta |
| E-03 | Gestión de Sesiones de Testeo | Alta |
| E-04 | Dashboard de Indicadores | Media |
| E-05 | Registro de Hallazgos | Media |
| E-06 | Sistema de Mejoras Sugeridas | Media |
| E-07 | Edición y Mantenimiento de Registros | Baja |
| E-08 | Documentación y Reportes | Alta |

---

## User Stories

### E-01: Módulo de Gestión de Tareas

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-01 | Crear módulo de registro de tareas | Frontend | Must (MoSCoW) | 5 SP | Pendiente | Formulario de registro con campos: nombre, descripción, prioridad, fecha límite, usuario asignado. Validación de campos obligatorios. |
| HU-01.1 | Listar todas las tareas registradas | Frontend | Must (MoSCoW) | 3 SP | Pendiente | Tabla con filtros por estado, prioridad y fecha. Paginación de resultados. |
| HU-01.2 | Eliminar tareas | Frontend | Should (MoSCoW) | 2 SP | Pendiente | Confirmación antes de eliminar. Registro en log de auditoría. |

### E-02: Módulo de Observaciones

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-02 | Implementar registro de observaciones | Frontend | Must (MoSCoW) | 5 SP | Pendiente | Registro de observaciones visible con campos: fecha, usuario, tipo observación, descripción, evidencia. Integración con tareas. |
| HU-02.1 | Filtrar observaciones por fecha y tipo | Frontend | Should (MoSCoW) | 3 SP | Pendiente | Filtros funcionales con resultados en tiempo real. |
| HU-02.2 | Exportar observaciones a PDF | Frontend | Could (MoSCoW) | 2 SP | Pendiente | Generación de reporte en formato PDF. |

### E-03: Gestión de Sesiones de Testeo

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-03 | Gestionar sesiones de testeo | Backend | Must (MoSCoW) | 8 SP | Pendiente | Sesiones creadas con: nombre, fecha, hora, participantes, escenario, tareas a evaluar. |
| HU-03.1 | Visualizar sesiones programadas | Frontend | Must (MoSCoW) | 5 SP | Pendiente | Listado visible con calendario integrado. Notificaciones de recordatorio. |
| HU-03.2 | Cerrar sesión de testeo | Backend | Should (MoSCoW) | 3 SP | Pendiente | Registro de cierre con resumen automático de observaciones registradas. |

### E-04: Dashboard de Indicadores

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-04 | Registrar indicadores de usabilidad | Backend | Must (MoSCoW) | 8 SP | Pendiente | Indicadores registrados: Tiempo de tarea, Tasa de éxito, Errors, Satisfacción (SUS). Cálculo automático de métricas. |
| HU-04.1 | Mostrar indicadores en dashboard | Frontend | Must (MoSCoW) | 5 SP | Pendiente | Dashboard con indicadores con gráficos interactivos. Comparativa entre sesiones. |
| HU-04.2 | Alertas por umbral de usabilidad | Backend | Could (MoSCoW) | 3 SP | Pendiente | Notificaciones cuando indicadores caen bajo umbrales definidos. |

### E-05: Registro de Hallazgos

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-05 | Crear interfaz para registrar hallazgos | Frontend | Must (MoSCoW) | 5 SP | Pendiente | Registro visual con campos: título, descripción, severity (crítico/moderado/leve), evidencia, sesión relacionada. |
| HU-05.1 | Clasificar hallazgos por severity | Frontend | Should (MoSCoW) | 3 SP | Pendiente | Filtros y badges visuales por tipo de severidad. |
| HU-05.2 | Notificar hallazgos críticos | Backend | Should (MoSCoW) | 2 SP | Pendiente | Alertas inmediatas para hallazgos de severity crítico. |

### E-06: Sistema de Mejoras Sugeridas

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-06 | Crear módulo de mejoras sugeridas | Backend | Must (MoSCoW) | 5 SP | Pendiente | Mejoras registradas con: descripción, justificación, prioridad, hallazgo relacionado. |
| HU-06.1 | Visualizar lista de mejoras | Frontend | Must (MoSCoW) | 3 SP | Pendiente | Listado visible con opciones de ordenamiento por prioridad y fecha. |
| HU-06.2 | Vincular mejora con hallazgo | Backend | Should (MoSCoW) | 2 SP | Pendiente | Relación uno a muchos entre hallazgos y mejoras. |

### E-07: Edición y Mantenimiento

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-07 | Implementar edición de registros | Fullstack | Should (MoSCoW) | 8 SP | Pendiente | Datos editables con control de versiones. Historial de cambios visible. |
| HU-07.1 | Eliminar registros con auditoría | Backend | Should (MoSCoW) | 3 SP | Pendiente | Soft delete con trazabilidad completa. |

### E-08: Documentación y Reportes

| ID | Título | Tipo | Prioridad | Estimación | Estado | Criterio de Aceptación |
|----|--------|------|-----------|------------|--------|----------------------|
| HU-08 | Elaborar documentación técnica del sistema | UX Researcher | Must (MoSCoW) | 5 SP | Completado | Documentación entregada con arquitectura,Manual de API, guía de instalación. |
| HU-08.1 | Elaborar documentación de usuario final | UX Researcher | Must (MoSCoW) | 3 SP | Completado | Manual de usuario con guía visual paso a paso. |
| HU-08.2 | Generar reporte final del test | Fullstack | Must (MoSCoW) | 8 SP | Pendiente | Resumen completo con métricas, hallazgos, recomendaciones y gráficos. |

---

## Dependencias entre User Stories

| User Story | Depende de |
|------------|-----------|
| HU-01.1 | HU-01 |
| HU-01.2 | HU-01 |
| HU-02.1 | HU-02 |
| HU-02.2 | HU-02 |
| HU-03.1 | HU-03 |
| HU-03.2 | HU-03 |
| HU-04.1 | HU-04 |
| HU-04.2 | HU-04.1 |
| HU-05.1 | HU-05 |
| HU-05.2 | HU-05 |
| HU-06.1 | HU-06 |
| HU-06.2 | HU-06, HU-05 |
| HU-07.1 | HU-07 |
| HU-08.2 | HU-04.1, HU-05.1, HU-06.1 |

---

## Fases Internas del Sprint

| Fase | Enfoque | Módulos Trabajados | Resultado Esperado |
|------|---------|-------------------|-------------------|
| Fase 1 — Base | Estructura inicial del sistema y diseño UX | Tareas, Observaciones, Sesiones, Wireframes | Sistema inicial funcional + flujo de pantallas |
| Fase 2 — Registro y testeo | Registro completo y sesiones con usuarios | Tareas, Observaciones, Sesiones, Testeo | Registro funcional + hallazgos documentados |
| Fase 3 — Análisis y documentación | Indicadores, mejoras y documentación | Indicadores, Hallazgos, Mejoras, Reporte | Dashboard funcional + documentación completa |

---

## Definition of Done (DoD)

| Criterio | Descripción |
|----------|-------------|
| Código funcional | La funcionalidad implementada ejecuta correctamente |
| Persistencia de datos | Los datos se guardan correctamente en base de datos |
| Interfaz usable | La interfaz es comprensible y usable |
| Validaciones aplicadas | Se validan datos obligatorios |
| Integración completa | Frontend y Backend funcionan correctamente |
| Pruebas con usuarios realizadas | Se ejecutaron sesiones de testeo y se documentaron hallazgos |
| Documentación actualizada | Documentación técnica y de usuario entregada |

---

## Resumen de Estimación Total

| Épica | Story Points |
|-------|-------------|
| E-01 | 10 SP |
| E-02 | 10 SP |
| E-03 | 16 SP |
| E-04 | 16 SP |
| E-05 | 10 SP |
| E-06 | 10 SP |
| E-07 | 11 SP |
| E-08 | 16 SP |
| **Total** | **99 SP** |

---

*Versión del backlog: 1.0*
*Última actualización: 15/05/2026*
*Owner: Equipo de Desarrollo UX*