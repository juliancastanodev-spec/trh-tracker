# Reglas del Proyecto (Spec-Driven Development)

## Flujo de trabajo obligatorio
1. **Fuente de verdad:** `docs/SPEC.md` define qué se construye. No implementes ninguna funcionalidad, pantalla o campo de datos que no esté especificado ahí.
2. **Planificación:** Toda implementación debe seguir el orden de tareas en `docs/TASKS.md`.
3. **Validación:** Antes de dar por terminada una tarea, escribí y ejecutá los tests que cubran sus criterios de aceptación. Si los tests no pasan, la tarea no está terminada.
4. **Dudas o ambigüedades:** Si algo en la spec no está claro o falta definir un borde, preguntá antes de asumir o inventar comportamiento.

## Principios de producto
- **Privacidad:** Los datos de salud del usuario son sensibles. Priorizá almacenamiento local y evitá telemetría o dependencias externas innecesarias.
- **Lenguaje y UI:** Tono neutro, inclusivo y no patologizante. Evitá estética o terminología que asuma género o anatomía cis.
