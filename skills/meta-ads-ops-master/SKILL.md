---
name: meta-ads-ops-master
description: When the user wants a repeatable Meta Ads operating system for one client and one monthly period, from structure and creative hypotheses to optimization rules. Reuses paid-ads, ad-creative, ab-test-setup, analytics-tracking, and page-cro.
---

## Cuándo usarla

- Al lanzar campañas en Meta (Facebook/Instagram).
- Al reestructurar cuenta o escalar inversión.
- Al planear ciclo mensual de pruebas y optimización.

## Inputs mínimos

- `client_slug`
- `periodo`
- Objetivo de campaña
- Presupuesto mensual
- Oferta/landing
- Audiencias disponibles

## Skills existentes a reutilizar

- `paid-ads`
- `ad-creative`
- `ab-test-setup`
- `analytics-tracking`
- `page-cro`

## Proceso paso a paso

1. Validar objetivo, presupuesto y evento de conversión.
2. Diseñar arquitectura de campaña/ad set/ad.
3. Definir audiencias por temperatura (frío/warm/hot).
4. Generar hipótesis creativas y variantes de copy.
5. Configurar plan de experimentación A/B.
6. Definir umbrales de decisión (pausar/escalar).
7. Consolidar plan operativo mensual.

## Formato de salida

- Archivo principal: `clients/<client_slug>/05-campaigns/meta-ads/<periodo>/campaign-architecture.md`
- Secciones mínimas:
  - Objetivo y evento
  - Estructura de campañas
  - Audiencias
  - Creativos y tests
  - Reglas de optimización

## Checklist de calidad

- [ ] Objetivo de negocio y métrica primaria alineados.
- [ ] Estructura contempla prospecting y remarketing.
- [ ] Plan de tests con hipótesis y criterio de corte.
- [ ] Tracking y UTMs definidos.

## Reglas para no mezclar clientes

- No reutilizar audiencias o resultados de otros clientes sin etiquetado.
- Mantener nomenclatura de campañas con `client_slug` y `periodo`.
- Guardar siempre en la ruta del cliente activo.
