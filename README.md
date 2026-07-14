# OpenCode para divulgación científica — taller

<p align="center">
  <img src="https://opencode.ai/logo.png" alt="OpenCode" width="200">
</p>

Presentación y materiales del taller *Asistente IA para el trabajo universitario*,
impartido en la Facultad de Biología de la Universidad de Murcia.

**Versión:** 1.0

## Contenido

| Archivo | Descripción |
|---------|-------------|
| `100-oc-divulga.qmd` | Fuente de la presentación (Quarto revealjs) |
| `100-oc-divulga.html` | Presentación autocontenida, listo para abrir en navegador |
| `dafo-presentacion.html` | Análisis DAFO de la presentación |
| `AGENTS.md` | Instrucciones y convenciones del proyecto para OpenCode |
| `LICENSE` | Licencia CC BY-NC-SA 4.0 |
| `VERSION` | Versión actual del material |

### Documentos de apoyo (`docs/`)

| Archivo | Descripción |
|---------|-------------|
| `bases-cambio-modelo.{qmd,html,pdf}` | Ensayo: del modelo de apps al de texto plano + agentes |
| `diagnostico-usuario.{qmd,html}` | Diagnóstico del perfil de usuario y sus dificultades |
| `faq-cambio-modelo.{qmd,html,pdf}` | Preguntas frecuentes sobre el cambio de modelo |
| `analisis-plantilla-ineficiente.qmd` | Análisis de una plantilla Word ineficiente |
| `analisis-plantillas-universitarias.qmd` | Análisis comparativo de plantillas universitarias |
| `custom.css` | Estilos compartidos para documentos Quarto |
| `cosmo-custom.scss` | Sobreescripciones del tema Cosmo (Bootstrap) |

## Estructura de la sesión

- **Introducción** — Bienvenida, objetivos, barreras al cambio, qué es OpenCode
- **Parte 1 — Primeros pasos** — Ejemplos prácticos: resumen, comparativa, fusión, formatos
- **Parte 2 — Un proyecto** — Caso completo sobre tejidos animales
- **Parte 3 — Más potencia** — Agentes, skills, MCP, Git
- **Cierre** — Conclusiones, próximos pasos, referencias

## Generar la presentación

```bash
quarto render 100-oc-divulga.qmd
```

Requiere [Quarto](https://quarto.org).

## Licencia

CC BY-NC-SA 4.0 — Ver archivo `LICENSE`.
