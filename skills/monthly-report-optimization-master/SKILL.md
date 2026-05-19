---
name: monthly-report-optimization-master
description: When the user wants to produce a monthly marketing performance report and optimization plan for one client. Use for KPI review, insights by channel, experiment outcomes, and next-month recommendations. Reuses analytics-tracking, paid-ads, ab-test-setup, revops, and churn-prevention when relevant.
---

## Cuándo usarla

- Al cierre de cada mes.
- En comités de rendimiento con cliente.
- Para decidir qué escalar, mantener o pausar.

## Inputs mínimos

- `client_slug`
- `periodo`
- KPIs del mes
- Resultados por canal
- Aprendizajes de experimentos
- Objetivos del siguiente mes

## Skills existentes a reutilizar

- `analytics-tracking`
- `paid-ads`
- `ab-test-setup`
- `revops`
- `churn-prevention` (si aplica)

## Proceso paso a paso

1. Consolidar KPIs contra metas.
2. Analizar desempeño por canal y etapa del funnel.
3. Revisar resultados de tests/experimentos.
4. Identificar causas raíz de desviaciones.
5. Definir acciones: pausar, mantener, escalar.
6. Priorizar backlog de optimización del mes siguiente.
7. Documentar riesgos y requerimientos del cliente.

## Formato de salida

- Archivo principal: `clients/<client_slug>/06-reporting/monthly/<periodo>/monthly-report.md`
- Secciones mínimas:
  - Resumen ejecutivo
  - KPIs vs meta
  - Insights por canal
  - Experimentos y aprendizajes
  - Plan de optimización siguiente mes

## Checklist de calidad

- [ ] Incluye comparación contra meta y contra mes anterior.
- [ ] Explica por qué pasó cada cambio relevante.
- [ ] Propone acciones concretas con prioridad y dueño.
- [ ] Define hipótesis para el próximo ciclo.

## Reglas para no mezclar clientes

- No consolidar datos de múltiples clientes en un mismo reporte.
- Verificar encabezado con `client_slug` y `periodo`.
- Mantener evidencia y anexos dentro de la carpeta del cliente.
