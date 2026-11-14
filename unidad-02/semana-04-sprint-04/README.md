# Semana 04: Sprint 04 — Recomendación Top-k, Feed XAI, Reserva ACID y Quórum

> **Curso:** SI-983 Construcción de Software I (Semestre 2026-II)  
> **Proyecto:** Sistema Web P2P con algoritmo de recomendación para la personalización de mentorías académicas en la EPIS-UPT  
> **Equipo (Grupo 03):** Renzo Antonio Antayhua Mamani & Joan Cristian Medina Quispe  

---

## 📌 1. Alcance del Incremento
Cálculo Top-k multifactorial con ponderación curricular de materias filtro (1.0x a 1.3x) y exclusión forzada de mérito (RN-03), Feed interactivo XAI (CUS02/CUS03), modal de reserva transaccional (CUS04) con ratificación obligatoria en T-24h (RN-08) y Ley N° 29733 (RN-02), coordinador transaccional ACID con bloqueo pesimista `SELECT ... FOR UPDATE` (RNF07) y corte de quórum del 50% (RN-09).

## 📊 2. Métricas de Calidad
* **Pruebas automatizadas:** 245 pruebas consolidadas (87 en frontend y 158 en backend, 100% de éxito).
* **Cobertura de código:** 92.56% frontend, 91.22% backend (superando ampliamente el 70% normativo de RNF09).
* **Sobrecupo:** 0.00% tasa de fallo en suite concurrente multihilo de 20 hilos.

## 📋 3. Documentación y Evidencias

| Documento | Tipo | Enlace |
| :--- | :--- | :--- |
| **Bitácora Principal Sprint 04** | Reporte Técnico | [sprint-04.md](sprint-04.md) |
| **Informe General Técnico** | Análisis Consolidado | [INFORME_GENERAL_SPRINT_04.md](INFORME_GENERAL_SPRINT_04.md) |
| **Evidencia de Pruebas Automatizadas** | Reporte QA | [EVIDENCIA_PRUEBAS_SPRINT_04.md](EVIDENCIA_PRUEBAS_SPRINT_04.md) |
| **Paquete Oficial de Presentación y Diapositivas** | Exposición | [`presentacion/`](presentacion/) |
| **Evidencias Gráficas del Sprint** | Capturas del Sistema | [`imagenes/sprint-04/`](imagenes/sprint-04/) |
