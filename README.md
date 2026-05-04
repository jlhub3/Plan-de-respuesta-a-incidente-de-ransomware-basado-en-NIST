# Resumen: Plan de Respuesta a Incidentes de Ransomware (NIST) - TechCo

Este repositorio contiene la síntesis estratégica del plan de respuesta ante incidentes diseñado para **TechCo**, estructurado bajo el marco de ciberseguridad **NIST CSF**. El proyecto detalla las acciones necesarias para mitigar el impacto de un ataque de ransomware y fortalecer la resiliencia organizacional.

---

## 📋 Ficha del Proyecto
*   **Autor:** Julio Fraga
*   **Versión:** 1.0
*   **Marco de Trabajo:** NIST (Identify, Protect, Detect, Respond, Recover)
*   **Caso de Estudio:** Respuesta técnica y administrativa ante cifrado de activos críticos.

---

## 📖 Tabla de Contenidos
1. Resumen Ejecutivo
2. Diagnóstico de Vulnerabilidades
3. Estrategia de Respuesta (NIST)
4. Acciones de Mejora Continua

---

## 1. Resumen Ejecutivo
El plan aborda la recuperación de capacidades operativas tras un compromiso masivo de datos. Se propone una transformación de la infraestructura de **TechCo**, priorizando la contención del movimiento lateral y la restauración de la base de datos de clientes mediante protocolos de seguridad avanzada.

## 2. Diagnóstico de Vulnerabilidades
Se identificaron tres fallos críticos en la postura de seguridad original:
*   **Arquitectura:** Red plana que permitió la propagación del malware.
*   **Backups:** Falta de inmutabilidad y aislamiento de las copias de seguridad.
*   **Acceso:** Ausencia de autenticación multifactor (MFA) y deficiencias en la detección de phishing.

## 3. Estrategia de Respuesta (NIST)
El plan se articula en las cinco funciones del framework:

*   **Identificación:** Inventario de activos críticos y evaluación del impacto legal por pérdida de datos PII.
*   **Protección:** Implementación de segmentación de red y política de backups **3-2-1-1** con copias *offline*.
*   **Detección:** Adopción de soluciones **EDR** y sistemas de alerta temprana para detectar cifrados anómalos.
*   **Respuesta:** Protocolo de aislamiento físico/lógico de sistemas y comunicación de crisis fuera de banda.
*   **Recuperación:** Restauración escalonada tras limpieza forense, priorizando la continuidad del negocio.

## 4. Acciones de Mejora Continua
Para fortalecer la defensa futura, el plan establece:
*   **Lecciones Aprendidas:** Análisis técnico post-incidente para el ajuste de controles.
*   **Entrenamiento:** Simulacros de respuesta ante ransomware para el personal técnico y administrativo.
*   **Validación:** Auditorías periódicas de los nuevos perímetros de seguridad.

---
*Documentación técnica elaborada por Julio Fraga.*
