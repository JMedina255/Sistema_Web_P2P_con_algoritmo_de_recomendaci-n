# Informe de Auditoría y Revisión Documental de Actas de Reunión (Unidad II)

> **Curso:** SI-983 Construcción de Software I (Semestre 2026-II)  
> **Proyecto:** Sistema Web P2P con algoritmo de recomendación para la personalización de mentorías académicas en la EPIS-UPT  
> **Equipo (Grupo 03):** Renzo Antonio Antayhua Mamani & Joan Cristian Medina Quispe  
> **Fecha de Auditoría:** 14 de Noviembre de 2026  
> **Ámbito Evaluado:** Actas 11 a 20 (Archivo fuente: `actas.zip`)  

---

## 📌 1. Alcance y Criterio de la Auditoría
En cumplimiento estricto de las directrices de integridad documental:
* Las actas 11 a 20 fueron transferidas de forma binaria íntegra a `unidad-02/semana-06-entrega-documentacion/actas/`.
* Se preservaron las actas 5 a 10 exclusivamente en la Unidad I (el Acta 10 corresponde al cierre documental de dicha unidad).
* **Se prohíbe la alteración del texto original de los archivos `.docx`** para no introducir correcciones históricas artificiales sin respaldo de cátedra.
* Todas las anomalías detectadas en la correlación o contenido se documentan a continuación y se declaran como **Pendientes de Validación**.

---

## 📋 2. Matriz de Estado y Hallazgos por Acta

| Archivo | Nro. Declarado en Nombre | Nro. Interno en Documento | Sprint / Asunto Principal en Cuerpo | Estado de Validación | Severidad | Hallazgos e Incidencias Identificadas |
| :--- | :---: | :---: | :--- | :---: | :---: | :--- |
| `G03_Acta_Reunion_11.docx` | 11 | 11 | Planificación Sprint 01 y acuerdos iniciales | ✅ Conforme | - | Sin inconsistencias detectadas. |
| `G03_Acta_Reunion_12.docx` | 12 | 12 | Seguimiento técnico de arquitectura | ✅ Conforme | - | Sin inconsistencias detectadas. |
| `G03_Acta_Reunion_13.docx` | 13 | 13 | Revisión de tareas Sprint 01 | ✅ Conforme | - | Sin inconsistencias detectadas. |
| `G03_Acta_Reunion_14.docx` | 14 | 14 | Coordinación técnica Sprint 02 | ✅ Conforme | - | Sin inconsistencias detectadas. |
| `G03_Acta_Reunion_15.docx` | 15 | 15 | Revisión de funcionalidades Sprint 03 | ✅ Conforme | - | Sin inconsistencias detectadas. |
| `G03_Acta_Reunion_16.docx` | 16 | **15** | Presentación objetivo y alcance Sprint 04 | ⚠️ **Pendiente de Validación** | Media | **Inconsistencia de correlativo:** El encabezado interno indica erróneamente *«Acta de Reunión Nro. 15»* en lugar de Nro. 16. |
| `G03_Acta_Reunion_17.docx` | 17 | **15** | Presentación objetivo y alcance Sprint 05 | ⚠️ **Pendiente de Validación** | Media | **Inconsistencia de correlativo:** El encabezado interno indica erróneamente *«Acta de Reunión Nro. 15»* en lugar de Nro. 17. |
| `G03_Acta_Reunion_18.docx` | 18 | **15** | Presentación objetivo y alcance Sprint 06 | ⚠️ **Pendiente de Validación** | Media | **Inconsistencia de correlativo:** El encabezado interno indica erróneamente *«Acta de Reunión Nro. 15»* en lugar de Nro. 18. |
| `G03_Acta_Reunion_19.docx` | 19 | 19 | Título: Sprint 07 / **Cuerpo: Sprint 06** | ⚠️ **Pendiente de Validación** | Alta | **Inconsistencia de contenido:** El encabezado anuncia el Sprint 07, pero el Punto 1 y los acuerdos describen textualmente el *Sprint 06* (quórum T-24h, 465 pruebas, asistencias y bitácoras). |
| `G03_Acta_Reunion_20.docx` | 20 | 20 | Título: Sprint 08 / **Cuerpo: Sprint 06** | ⚠️ **Pendiente de Validación** | Alta | **Inconsistencia de contenido:** El encabezado anuncia el Sprint 08, pero el cuerpo replica exactamente la descripción del *Sprint 06*. |

---

## 🔍 3. Detalle de Incidencias Técnicas

### 3.1. Discrepancia de Encabezado en Actas 16, 17 y 18
* **Diagnóstico:** Reutilización de la plantilla del Acta 15 sin actualizar el campo de texto del número de reunión en el encabezado.
* **Impacto:** Confusión en la lectura del documento impreso respecto a la minuta que representa.
* **Acción de Conservación:** Se mantienen intactos los binarios originales para preservar las firmas y sellos históricos. Se reporta para regularización formal ante el docente.

### 3.2. Duplicación de Contenido de Sprint 06 en Actas 19 y 20
* **Diagnóstico:** Copia del bloque temático del Sprint 06 en las actas correspondientes a las sesiones de los Sprints 07 y 08.
* **Impacto:** Falta de registro formal en formato Word de las deliberaciones específicas sobre visado de horas (Sprint 07) y demostración final (Sprint 08), aunque dichas actividades están plenamente documentadas en los reportes técnicos Markdown (`sprint-07.md` y `sprint-08.md`).
* **Acción de Conservación:** Se mantiene el documento tal como fue emitido por el equipo, marcándolo explícitamente en el Pull Request.

---

## 📌 4. Acta Técnica Complementaria
Adicionalmente, se incorpora el acta en formato Markdown:
* [`ACTA_CIERRE_SPRINT_02.md`](ACTA_CIERRE_SPRINT_02.md): Acta técnica de cierre formal del Sprint 02, suscrita por Joan Medina y Renzo Antayhua, que certifica el cumplimiento de las tareas T-04, T-10, T-11 y la suite de pruebas Vitest.
