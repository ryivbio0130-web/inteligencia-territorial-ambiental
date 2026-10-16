# Acta de Constitución del Proyecto

| Campo | Información |
|---|---|
| Nombre | Sistema de Inteligencia Territorial y Valoración Económica Ambiental (PIT-VEA) |
| Naturaleza | Iniciativa académica individual con proyección a consultoría |
| Inicio | 10 de septiembre de 2026 |
| Entrega académica de referencia | 4 de noviembre de 2026 (semana 8) |
| Horizonte de desarrollo | 24 semanas; hasta el 24 de febrero de 2027 |
| Dedicación | 7–8 h/semana (180 h de planeación; intervalo 168–192 h) |
| Responsable / director / desarrollador | Estudiante promotor del proyecto — Ricardo Ibarguen |
| Docente evaluador | Cesar Augusto Espinosa Vargas|
| Patrocinador financiero | No identificado; no se presume financiación |
| Versión y estado | 2.0 — borrador para validación académica |

## 1. Antecedentes y justificación
Existe un prototipo en notebook Python de ingesta ambiental y de biodiversidad, análisis geoespacial, agrupamiento K-means, conectividad, estimaciones económicas, mapas e informes. El análisis de las versiones anteriores detectó dependencias de notebook, funciones incompletas, rutas específicas, simulaciones implícitas y supuestos económicos que requieren validación. **La existencia de código no implica que todos los cálculos estén validados.**

El proyecto busca transformar este prototipo en una herramienta de uso individual que facilite estudios repetibles en territorios de Colombia, con resultados trazables y adecuados para servicios de consultoría ambiental.

## 2. Objetivo general
Diseñar, desarrollar y validar progresivamente una herramienta modular de inteligencia territorial y valoración económica ambiental, reutilizable en distintos territorios de Colombia, que integre información geoespacial y ecológica verificable, aplique modelos documentados y genere productos técnicos para apoyar la prestación futura de servicios profesionales de consultoría.

## 3. Objetivos específicos
1. Organizar y documentar el prototipo existente, sus capacidades y limitaciones.
2. Parametrizar la delimitación territorial y las fuentes de datos, evitando rutas y supuestos fijos.
3. Implementar controles de calidad y procedencia que impidan presentar datos simulados como observaciones reales.
4. Evaluar y fortalecer indicadores espaciales, conectividad y clustering con criterios estadísticos y ecológicos.
5. Diseñar un módulo de valoración económica sustentado en superficies elegibles, metodologías explícitas e incertidumbre.
6. Generar mapas, datos exportables e informes técnicos verificables.
7. Establecer un flujo profesional reutilizable para futuros encargos de consultoría.

## 4. Alcance inicial
**Durante el periodo académico (semanas 1–8):** acta, interesados, visión, alcance, EDT, cronograma, presupuesto, riesgos; organización del repositorio; diagnóstico de código; parametrización territorial inicial y prueba controlada de un flujo parcial, si se satisfacen sus dependencias. **No se promete una plataforma terminada para la semana 8.**

**Posteriormente (semanas 9–24):** refactorización progresiva, ingesta robusta, controles de calidad, modelado validado, productos de consultoría y pruebas de un MVP personal.

**Fuera del alcance inicial:** SaaS, gestión de múltiples clientes dentro del software, pagos, licenciamiento, cobertura científica validada de todos los ecosistemas, trabajo de campo y aval oficial de valoraciones.

## 5. Entregables
| Código | Entregable | Hito | Evidencia esperada |
|---|---|---|---|
| A1 | Acta, visión y matriz de interesados | Semana 5 | Páginas Wiki + Excel |
| A2 | Alcance, EDT/WBS, Gantt, presupuesto y riesgos | Semana 6 | Páginas Wiki + Excel |
| A3 | Repositorio y diagnóstico técnico | Semana 7 | Código versionado, inventario y registro de problemas |
| A4 | Demostración controlada e informe de avance | Semana 8 | Registro de ejecución, resultados, límites y capturas/archivos |
| P1 | Motor territorial parametrizable | Posterior | Pruebas con geometrías diferentes |
| P2 | Datos y modelos validados | Posterior | Trazabilidad, métricas y pruebas |
| P3 | Productos profesionales y MVP personal | Posterior | Exportaciones e informe piloto |

## 6. Interesados y roles
- **Promotor/desarrollador Ricardo Ibarguen:** dirección, análisis, programación, pruebas, documentación y decisiones de alcance.
- **Docente o tutor académico Cesar Augusto Espinosa Vargas:** evaluación y orientación; no se le asignan tareas de desarrollo.
- **Especialistas SIG, ecología y economía ambiental (potenciales):** revisión metodológica puntual; participación no confirmada.
- **Clientes potenciales:** retroalimentación sobre utilidad de los productos; no son financiadores confirmados.
- **Proveedores de datos:** fuentes sujetas a términos de uso y disponibilidad.

Ver [Análisis de Interesados](Analisis-de-Interesados).

## 7. Recursos, supuestos y restricciones
- Capacidad individual de 7–8 horas semanales; no hay equipo contratado.
- Se reutiliza el notebook existente; la estimación no supone desarrollar desde cero.
- La infraestructura y las tarifas se presupuestan como escenarios, no como gastos aprobados.
- La valoración económica solo se publicará como resultado sustentado si existe método, datos y validación suficientes.
- El calendario de semanas académicas es una **línea base propuesta** a confirmar con el calendario oficial del curso.

## 8. Riesgos prioritarios
Falta de tiempo, dependencia de una sola persona, simulaciones involuntarias, fallos de fuentes externas, geometrías incorrectas, sesgos de clustering y estimaciones económicas no defendibles. Ver [Matriz de Riesgos](Matriz-de-Riesgos).

## 9. Criterios de aceptación
**Semana 8:** documentación requerida publicada; repositorio identificado; inventario de funcionalidades; una ejecución parcial demostrada o, si está bloqueada, registro reproducible de fallos y plan de corrección.  
**MVP posterior:** estudio territorial parametrizado, resultados con procedencia, controles de calidad, exportaciones e informe técnico; no se obliga a incluir valoración económica si no supera validación.

## 10. Aprobación
| Rol | Nombre | Fecha | Estado |
|---|---|---|---|
| Promotor del proyecto | Por completar | — | Pendiente |
| Docente evaluador, si corresponde | Por completar | — | Pendiente |

[Inicio](Home) · [Acta](Acta-de-Constitucion) · [Interesados](Analisis-de-Interesados) · [Visión](Vision-del-Proyecto) · [Alcance y EDT](Alcance-del-Proyecto) · [Cronograma](Cronograma-del-Proyecto) · [Presupuesto](Presupuesto-del-Proyecto) · [Riesgos](Matriz-de-Riesgos) · [Avance semana 8](Hito-Academico-Semana-8) · [Arquitectura](Arquitectura-Tecnica)
