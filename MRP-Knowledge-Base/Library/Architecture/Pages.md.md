---
title: App Pages
title_es: Páginas de la App
tags: [architecture, ui]
related: [Entities, MrPChat]
description_en: Core pages and workflows for MRP.
description_es: Páginas y flujos centrales para MRP.
category_en: Architecture
category_es: Arquitectura
lang: bilingual
---
# App Pages / Páginas de la App

## Definition / Definición
- En: Responsive layouts: Home, Dashboard, Survey, MrPChat, Library, Detail.
- Es: Diseños responsivos: Home, Dashboard, Survey, MrPChat, Library, Detail.

## Key Elements / Elementos Clave
- En: Home: Hero, tiers (PathCards), signup.
- Es: Home: Hero, tiers (PathCards), registro.
- En: Dashboard: CreditBalance, upgrades via Stripe.
- Es: Dashboard: CreditBalance, upgrades vía Stripe.
- En: Survey: 8 steps, LLM RAG generation.
- Es: Survey: 8 pasos, generación RAG LLM.

## Connections / Conexiones
- En: Workflows link to Entities; gated by tiers.
- Es: Flujos enlazan a Entities; gateados por tiers.

## Metrics & Implementation / Métricas e Implementación
- En: Load times: Home <2s, Dashboard <1s refresh.
- Es: Tiempos carga: Home <2s, Dashboard <1s refresh.
- Goal: 90% navigation to Chat/Library in-session for 1M MAU.