---
name: competitor-benchmark-master
description: When the user wants a repeatable competitor benchmark across social and digital channels for a specific client. Use for competitor mapping, comparative messaging, channel analysis, and opportunity gap detection. Reuses competitor-profiling, competitor-alternatives, social-content, and paid-ads.
---

## Cuándo usarla

- Al inicio de estrategia o relanzamiento.
- Antes de definir parrilla o campañas pagadas.
- En revisiones trimestrales de posicionamiento.

## Inputs mínimos

- `client_slug`
- `periodo`
- Lista de competidores (3-8)
- Canales a comparar (social, ads, SEO, web)
- Objetivo del benchmark

## Skills existentes a reutilizar

- `competitor-profiling`
- `competitor-alternatives`
- `social-content`
- `paid-ads`

## Proceso paso a paso

1. Validar lista de competidores y alcance del benchmark.
2. Estandarizar criterios de comparación.
3. Perfilar competidores en formato comparable.
4. Analizar contenido social (mensajes, formatos, frecuencia).
5. Analizar pauta digital (ofertas, CTA, ángulos).
6. Identificar brechas: copiar, evitar, diferenciar.
7. Priorizar oportunidades para 30 días.

## Formato de salida

- Archivo principal: `clients/<client_slug>/03-benchmark/competitor-benchmark.md`
- Secciones mínimas:
  - Metodología
  - Matriz comparativa
  - Hallazgos por canal
  - Oportunidades accionables
  - Recomendaciones priorizadas

## Checklist de calidad

- [ ] Criterios homogéneos para todos los competidores.
- [ ] Hallazgos basados en evidencia, no supuestos.
- [ ] Oportunidades priorizadas por impacto/esfuerzo.
- [ ] Conecta hallazgos con estrategia del cliente.

## Reglas para no mezclar clientes

- Guardar benchmark solo en carpeta del `client_slug` activo.
- Nunca mezclar lista de competidores entre clientes.
- Etiquetar fecha y periodo en el documento.
