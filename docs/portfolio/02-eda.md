---
title: "EDA mínimo reproducible"
date: 2026-07-12
---

# EDA mínimo reproducible

## Objetivo

Verificar que una segunda evidencia creada desde la plantilla aparece en la navegación y puede alcanzar el estado **Mínimo**.

## Evidencia

- Se registró la estructura esperada de un análisis exploratorio.
- El mapa enlaza esta entrada y conserva el estado en Git.
- No se incluyeron datos personales ni secretos.

## Reproducibilidad

```bash
python scripts/validate_portfolio.py --root .
python -m mkdocs build --strict
```

## Decisiones y límites

Esta es una evidencia sintética de aceptación. Comprueba estructura, enlaces y publicación, pero no representa una evaluación estudiantil ni analiza un dataset real.

## Uso de IA

Nivel A1: se usó asistencia para preparar el fixture; el contenido y los comandos fueron verificados localmente.

## Microdefensa

El mapa Markdown es la fuente de verdad. JavaScript solo resume sus estados y el workflow bloquea la publicación si falta esta entrada o alguna sección obligatoria.
