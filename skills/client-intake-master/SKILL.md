---
name: client-intake-master
description: When the user wants to run a standardized initial client diagnosis for multi-client marketing operations without mixing context between clients. Use when the user mentions intake, onboarding, discovery, initial diagnosis, client audit, or baseline assessment. Reuses product-marketing-context, customer-research, analytics-tracking, and seo-audit.
---

## Cuándo usarla

- Cuando inicia un cliente nuevo.
- Cuando un cliente existente cambia oferta, ICP o canales prioritarios.
- Cuando necesitas actualizar la línea base de métricas y diagnóstico.

## Inputs mínimos

- `client_slug` (único, kebab-case).
- `periodo` (`YYYY-MM`).
- URL principal del negocio.
- Oferta principal.
- ICP / audiencia objetivo.
- Objetivos de negocio del trimestre.

## Skills existentes a reutilizar

- `product-marketing-context`
- `customer-research`
- `analytics-tracking`
- `seo-audit`
- `social-content` (si hay diagnóstico de redes)

## Proceso paso a paso

1. Validar `client_slug` y `periodo`.
2. Confirmar que toda salida irá a `clients/<client_slug>/...`.
3. Construir o actualizar el contexto de producto (base de posicionamiento).
4. Ejecutar investigación de cliente (VOC, fricciones, motivaciones, objeciones).
5. Auditar tracking y calidad de medición.
6. Auditar estado SEO técnico/on-page.
7. Consolidar hallazgos en diagnóstico priorizado por impacto.
8. Proponer quick wins (2 semanas) y plan 30/60/90.

## Formato de salida

- Archivo principal: `clients/<client_slug>/01-discovery/diagnosis.md`
- Secciones mínimas:
  - Resumen ejecutivo
  - Estado actual por canal
  - Hallazgos críticos
  - Oportunidades priorizadas
  - Quick wins
  - Riesgos y dependencias

## Checklist de calidad

- [ ] El slug del cliente aparece en el documento.
- [ ] El periodo `YYYY-MM` está explícito.
- [ ] Incluye evidencia por canal (no opiniones sueltas).
- [ ] Hay prioridades (alto/medio/bajo o ICE).
- [ ] Incluye acciones concretas para próximos 30 días.

## Reglas para no mezclar clientes

- Nunca escribir en rutas globales durante el trabajo del cliente.
- Nunca reutilizar métricas de otro slug.
- Antes de guardar, confirmar ruta destino con patrón `clients/<client_slug>/...`.
- Si falta `client_slug`, detener y solicitarlo.
