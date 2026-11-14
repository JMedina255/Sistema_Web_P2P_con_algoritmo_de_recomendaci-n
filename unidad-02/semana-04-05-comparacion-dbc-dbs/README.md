# Semana 04–05: Comparación de Desarrollo Basado en Componentes (DBC) vs. Basado en Servicios (DBS)

> **Curso:** SI-983 Construcción de Software I (Semestre 2026-II)  
> **Proyecto:** Sistema Web P2P con algoritmo de recomendación para la personalización de mentorías académicas en la EPIS-UPT  
> **Equipo (Grupo 03):** Renzo Antonio Antayhua Mamani & Joan Cristian Medina Quispe  

---

## 📌 1. Descripción de la Actividad
Estudio comparativo, contraste arquitectónico y criterios de selección entre el **Desarrollo Basado en Componentes (DBC / CBD)** y el **Desarrollo Basado en Servicios (DBS / SOA / RESTful)** en el marco de la construcción de sistemas web universitarios.

## 🎯 2. Aplicación Arquitectónica en el Sistema
* **Enfoque DBC (Frontend):** Arquitectura modular de componentes atómicos y reutilizables en **React 19 / TypeScript** (modales de consentimiento, tablas de disponibilidad, tarjetas explicables XAI, componentes de reserva y visores de asistencia).
* **Enfoque DBS (Backend):** Arquitectura desacoplada basada en servicios RESTful con **FastAPI** (`auth_service`, `offer_service`, `recommendation_service`, `booking_service`, `quorum_service`, `attendance_service`) comunicados mediante contratos OpenAPI 3.0 / DTOs Pydantic v2.

## 📋 3. Estado de los Entregables

| Artefacto | Tipo | Estado | Observaciones |
| :--- | :--- | :---: | :--- |
| **Informe Monográfico DBC vs. DBS** | Informe Académico | ⚠️ Pendiente | Documento teórico de aula virtual pendiente de incorporación física por los autores. |
| **Especificación de Arquitectura de Servicios y Componentes** | Documento SAD | ✅ Verificado en Repo | Modelo 4+1 Vistas formalizado en [SAD.md](../semana-06-entrega-documentacion/documentos-finales/SAD.md) (Vista de Desarrollo y Vista Lógica). |
