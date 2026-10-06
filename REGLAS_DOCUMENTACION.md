# Reglas y Estándares de Documentación del Repositorio

> **Curso:** SI-983 Construcción de Software I (Semestre 2026-II)  
> **Institución:** Universidad Privada de Tacna — EPIS  
> **Equipo:** Grupo 03 — Renzo Antonio Antayhua Mamani & Joan Cristian Medina Quispe  

Este documento define las directrices y estándares obligatorios para la organización, versionamiento, nomenclatura y mantenimiento de los entregables y evidencias académicas en este repositorio.

---

## 1. Organización Cronológica por Semanas
* La estructura de cada unidad académica se distribuye en carpetas nombradas por semana y actividad (ej. `semana-01-planteamiento`, `semana-02-modelo-canvas`, etc.).
* Cada carpeta semanal concentra únicamente los entregables y evidencias correspondientes a dicha etapa pedagógica.

## 2. Conservación de Versiones Históricas
* Se prohíbe la eliminación destructiva o sobreescritura ciega de versiones preliminares o borradores que formen parte de la evolución del proyecto.
* Cuando existan versiones intermedias de un entregable (ej. borradores del SRS o del Catálogo de Pruebas), estas deben coexistir en subcarpetas específicas (como `borradores/`) o con sufijos distintivos que reflejen su ciclo evolutivo.

## 3. Nomenclatura Formal de Documentos
* Los documentos formales deben seguir una convención clara y estandarizada:
  * Informes de Factibilidad y Visión: `FD01-Informe-Factibilidad.*`, `FD02-Informe-Vision.*`
  * Especificación de Requerimientos: `FD03-SRS-v1.0.*`, `FD03-SRS-Mejorado-v2.0.*`
  * Arquitectura de Software: `FD04-SAD-v1.0.*`
  * Propuesta de Proyecto: `FD06-Informe-Propuesta-Proyecto.*`
  * Actas de Reunión: `G03_Acta_Reunion_X.*`
  * Catálogos y cronogramas: nombres claros separados por guiones o guiones bajos normalizados.

## 4. Uso Obligatorio de `README.md` por Actividad
* Cada carpeta de semana o actividad debe incluir un archivo `README.md` que detalle:
  * Título y descripción de la actividad.
  * Objetivos pedagógicos y técnicos.
  * Lista de artefactos contenidos y enlaces relativos hacia los mismos.
  * Notas sobre el estado o dependencias de la evidencia.

## 5. Integridad y No Alteración de Fechas Históricas
* Los metadatos y fechas de elaboración consignados en los encabezados, actas y matrices corresponden estrictamente al momento histórico de su formulación en clase.
* Se prohíbe adulterar fechas históricas de entrega o minutas de reunión.

## 6. Convención de Commits Descriptivos
* Los mensajes de confirmación en Git deben ser claros, atómicos y descriptivos, utilizando prefijos convencionales en español (ej. `docs:`, `feat:`, `chore:`, `refactor:`, `test:`).
* Cada commit debe registrar una unidad de trabajo lógica coherente.

## 7. Codificación UTF-8 e Idioma Español
* Todos los documentos de texto plano y Markdown (`.md`) deben codificarse exclusivamente en formato **UTF-8 sin BOM**.
* La redacción técnica se realiza en idioma español con rigor académico y terminología formal de ingeniería de software.

## 8. Modelado y Diagramación Técnica
* Los diagramas de arquitectura, actividades y secuencia se expresan preferentemente en sintaxis declarativa **PlantUML** o **Mermaid**, facilitando su trazabilidad bajo control de versiones.
* Cuando se incluyan imágenes compiladas (`.png`), estas deben provenir de fuentes trazables del proyecto.

## 9. Política Contra Reemplazos Silenciosos
* Queda terminantemente prohibido reemplazar silenciosamente un documento existente sin registrar la motivación del cambio y su impacto en las matrices de trazabilidad del proyecto.
