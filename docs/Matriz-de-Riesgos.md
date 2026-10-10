# Matriz de Riesgos

## Escala
Probabilidad (P) e impacto (I): **1 bajo, 2 medio, 3 alto**. Exposición = P × I. Nivel: **1–2 bajo, 3–4 medio, 6–9 alto**. Valores preliminares.

| ID | Riesgo | P | I | Nivel | Prevención | Contingencia |
|---|---|---:|---:|---|---|---|
| R01 | Sobrecarga por ejecución individual | 3 | 3 | Alto (9) | Priorizar hito 8; limitar alcance; revisión semanal | Reducir módulos y reprogramar fases |
| R02 | Dependencia de notebook y funciones faltantes | 3 | 3 | Alto (9) | Inventario, entorno reproducible, pruebas mínimas | Presentar fallo reproducible y corrección priorizada |
| R03 | Datos simulados confundidos con reales | 2 | 3 | Alto (6) | Bandera de procedencia; prohibir fallback silencioso | Invalidar salida y repetir con fuente real |
| R04 | Fuentes externas inaccesibles | 3 | 2 | Alto (6) | Reintentos, caché, registro de fuente | Usar dataset real descargado con versión y licencia |
| R05 | Superficies y geometrías no representativas | 3 | 3 | Alto (9) | CRS, geometrías válidas, cobertura cartográfica | Suspender valoración de área y reportar limitación |
| R06 | K-means no validado o función ausente | 3 | 2 | Alto (6) | Prueba de función, silhouette y sensibilidad | Desactivar módulo y registrar error |
| R07 | Valoración económica arbitraria o doble conteo | 3 | 3 | Alto (9) | Métodos por servicio y áreas elegibles | No publicar cifra monetaria |
| R08 | Restricciones de licencias y datos sensibles | 2 | 3 | Alto (6) | Inventario de licencias y políticas de publicación | Restringir difusión y sustituir fuente |
| R09 | Inconsistencia entre PDF y resultados | 2 | 2 | Medio (4) | Plantillas alimentadas desde salidas verificadas | Entregar resultados tabulares con advertencia |
| R10 | Desfase con calendario académico | 2 | 3 | Alto (6) | Confirmar fechas con docente; checklist S5/S6 | Entregar primero documentos obligatorios |

**Responsable de seguimiento:** promotor/desarrollador (única persona asignada). Los especialistas externos son apoyo potencial, no responsables comprometidos.

**Archivo editable:** `Matriz-Riesgos.xlsx`. Revisiones previstas: semanas 5, 6, 8 y al finalizar cada fase posterior.

[Inicio](Home) · [Acta](Acta-de-Constitucion) · [Interesados](Analisis-de-Interesados) · [Visión](Vision-del-Proyecto) · [Alcance y EDT](Alcance-del-Proyecto) · [Cronograma](Cronograma-del-Proyecto) · [Presupuesto](Presupuesto-del-Proyecto) · [Riesgos](Matriz-de-Riesgos) · [Avance semana 8](Hito-Academico-Semana-8) · [Arquitectura](Arquitectura-Tecnica)
