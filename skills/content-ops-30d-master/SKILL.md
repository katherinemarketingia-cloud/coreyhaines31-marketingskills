---
name: content-ops-30d-master
description: When the user wants to turn content strategy into a 30-day publishing grid (12-20 posts) for one client. Use for monthly editorial operations, platform mix planning, and post-level production guidance. Reuses content-strategy, social-content, copywriting, image, and video.
---

## Cuándo usarla

- Después de definir estrategia de contenido.
- Al iniciar cada nuevo mes de ejecución.
- Cuando se requiere parrilla editorial multicanal.

## Inputs mínimos

- `client_slug`
- `periodo`
- Objetivos del mes
- Canales activos
- Recursos disponibles (equipo, diseño, video)
- Restricciones de marca

## Skills existentes a reutilizar

- `content-strategy`
- `social-content`
- `copywriting`
- `image`
- `video`

## Proceso paso a paso

1. Cargar estrategia vigente y objetivos mensuales.
2. Definir mix de formatos por canal.
3. Seleccionar 12-20 piezas con objetivo claro.
4. Redactar brief mínimo por publicación.
5. Definir CTA y activo creativo requerido.
6. Balancear awareness, consideración y conversión.
7. Consolidar calendario y estados de producción.

## Formato de salida

- Archivo principal: `clients/<client_slug>/04-content/monthly/<periodo>/content-calendar-30d.md`
- Secciones mínimas:
  - Resumen de estrategia mensual
  - Calendario tabular
  - Briefs por pieza
  - Requerimientos de diseño/video

## Checklist de calidad

- [ ] 12 a 20 publicaciones definidas.
- [ ] Cada pieza tiene objetivo, hook y CTA.
- [ ] Distribución equilibrada por canal/funnel.
- [ ] Fechas y estado de ejecución visibles.

## Reglas para no mezclar clientes

- No copiar parrillas entre slugs sin adaptación explícita.
- Mantener naming de activos con `client_slug` + `periodo`.
- Verificar carpeta del mes antes de guardar.
