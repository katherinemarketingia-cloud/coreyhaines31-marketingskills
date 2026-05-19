---
name: marketing-proposal-master
description: When the user wants to turn diagnosis findings into a structured marketing proposal for one client and one period, ensuring reusable channel strategy without cross-client contamination. Use for proposal creation, scope definition, roadmap 30/60/90, and KPI planning. Reuses marketing-ideas, content-strategy, paid-ads, page-cro, and pricing-strategy as needed.
---

## Cuándo usarla

- Después de terminar diagnóstico inicial.
- Cuando el cliente pide propuesta trimestral o mensual.
- Cuando necesitas alinear alcance, entregables y KPIs.

## Inputs mínimos

- `client_slug`
- `periodo`
- Diagnóstico previo del cliente
- Objetivos de negocio
- Presupuesto aproximado
- Canales prioritarios

## Skills existentes a reutilizar

- `marketing-ideas`
- `content-strategy`
- `paid-ads`
- `page-cro`
- `pricing-strategy` (si aplica)

## Proceso paso a paso

1. Cargar diagnóstico del cliente activo.
2. Definir objetivo principal y objetivos secundarios.
3. Traducir hallazgos en hipótesis de crecimiento.
4. Diseñar estrategia por canal con prioridades.
5. Construir roadmap 30/60/90 con entregables.
6. Definir KPIs, metas y cadencia de revisión.
7. Documentar dependencias del cliente y riesgos.

## Formato de salida

- Archivo principal: `clients/<client_slug>/02-strategy/marketing-proposal.md`
- Secciones mínimas:
  - Objetivos
  - Hipótesis
  - Estrategia por canal
  - Roadmap
  - KPIs y metas
  - Alcance / fuera de alcance

## Checklist de calidad

- [ ] La propuesta deriva explícitamente del diagnóstico.
- [ ] Incluye metas medibles por canal.
- [ ] El roadmap tiene fechas y responsables.
- [ ] Las recomendaciones respetan presupuesto y capacidad.

## Reglas para no mezclar clientes

- No reutilizar propuestas de otros clientes sin adaptar contexto.
- Referenciar solo documentos del mismo `client_slug`.
- Verificar encabezado con cliente y periodo antes de entregar.
