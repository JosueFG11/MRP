---
title: AI Security Guidelines
title_es: Directrices de Seguridad de IA
tags: [agent-config, security, ach]
related: [Persona, Guidelines]
description_en: Best practices to mitigate key threats in AI applications, including prompt injection, data leakage, and model poisoning, ensuring secure operations for agents like Mr.P.
description_es: Mejores prácticas para mitigar amenazas clave en aplicaciones de IA, incluyendo inyección de prompts, fugas de datos y envenenamiento de modelos, asegurando operaciones seguras para agentes como Mr.P.
category_en: Practice
category_es: Práctica
lang: bilingual
---
# AI Security Guidelines / Directrices de Seguridad de IA

## Definition / Definición
- En: Best practices to mitigate key threats in AI applications, including prompt injection, data leakage, and model poisoning, ensuring secure operations for agents like Mr.P.
- Es: Mejores prácticas para mitigar amenazas clave en aplicaciones de IA, incluyendo inyección de prompts, fugas de datos y envenenamiento de modelos, asegurando operaciones seguras para agentes como Mr.P.

## Key Elements / Elementos Clave
- En: **Prompt Injection Mitigation**: Constrain model behavior with system prompts limiting roles and responses; validate output formats; filter inputs/outputs semantically; enforce least privilege access; require human approval for high-risk actions; segregate external content; conduct adversarial testing.
- Es: **Mitigación de Inyección de Prompts**: Restringir comportamiento del modelo con prompts de sistema que limitan roles y respuestas; validar formatos de salida; filtrar entradas/salidas semánticamente; aplicar acceso de menor privilegio; requerir aprobación humana para acciones de alto riesgo; segregar contenido externo; realizar pruebas adversarias.
- En: **Data Leakage Prevention**: Implement input sanitization and validation; use role-based access controls (RBAC) and multi-factor authentication (MFA); monitor anomalies in real-time; minimize data exposure; audit periodically; apply zero-trust architecture.
- Es: **Prevención de Fugas de Datos**: Implementar sanitización y validación de entradas; usar controles de acceso basados en roles (RBAC) y autenticación multifactor (MFA); monitorear anomalías en tiempo real; minimizar exposición de datos; auditar periódicamente; aplicar arquitectura de confianza cero.
- En: **Model Poisoning Defense**: Validate data provenance and cross-validate subsets; detect anomalies with statistical methods; maintain backups for rollback; conduct red teaming and audits; enforce rate limiting; integrate runtime monitoring with SIEM.
- Es: **Defensa contra Envenenamiento de Modelos**: Validar procedencia de datos y cross-validar subconjuntos; detectar anomalías con métodos estadísticos; mantener respaldos para reversión; realizar red teaming y auditorías; aplicar límites de tasa; integrar monitoreo en tiempo real con SIEM.

## Connections / Conexiones
- En: Integrate into Mr.P's core philosophy for safe ACH interactions; link to awareness_profile for personalized threat detection; align with app tiers for enhanced monitoring in higher levels.
- Es: Integrar en la filosofía central de Mr.P para interacciones ACH seguras; enlazar a awareness_profile para detección de amenazas personalizada; alinear con tiers de app para monitoreo mejorado