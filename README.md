# 360-recursos

Biblioteca de recursos formativos de 360º Consulting. HTML estático desplegado en Vercel.

## Primera edición

**Excelenc-IA** — Formación IA para Spain Is Excellence (21-22 abril 2026).

## Stack

- HTML vanilla + CSS variables + JS puro (sin dependencias)
- Fuentes: Playfair Display + Jost (Google Fonts)
- Paleta 360º: `#F4E711` amarillo + `#0A0A0A` fondo
- Deploy: Vercel vía GitHub (auto-deploy on push)

## Estructura

```
/                   Landing (grid de recursos + CTAs)
/prompts/           Kit de Prompts por Workflow
/toolkit/           Toolkit Mobile-First
/framework/         Framework CORF
/roadmap/           Roadmap 3 Fases
/datos/             Guía de Análisis de Datos + CSV descargable
/assets/            Logos, CSS global, dataset CSV
robots.txt          Disallow / (no indexable)
```

## Workflow para futuras formaciones

1. Crear nuevos .md en `Life OS/02. Areas/business_360/clientes/activos/[cliente]/materiales-formacion/`
2. Adaptar `/tmp/md2html.py` con los nuevos metadatos
3. Regenerar páginas
4. Push → auto-deploy

## Contenido fuente

Los `.md` originales viven en:
`~/Desktop/Life OS/02. Areas/business_360/clientes/activos/Spain Is Excellence/materiales-formacion/`
