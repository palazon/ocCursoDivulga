# Sesión: OpenCode para gestión universitaria

<p align="center">
  <img src="https://opencode.ai/logo.png" alt="OpenCode" width="200">
</p>

## Datos de la sesión

| Campo | Valor |
|-------|-------|
| **Fecha** | 2 de julio de 2026 |
| **Hora** | 9:30 - 11:30 (2 horas) |
| **Lugar** | Aulario de la Facultad de Biología |
| **Audiencia** | Creadores de contenido universitario (no programadores) |
| **Confirmación** | xxx@um.es |

## Objetivo

Taller práctico de 2 horas para que creadores de contenido universitario
descubran OpenCode como asistente de IA que trabaja en su ordenador:
resumir, comparar, fusionar documentos, generar presentaciones, crear
proyectos, automatizar tareas repetitivas.

## Estructura de la sesión

### Intro y contexto

- Bienvenida, objetivos, barreras al cambio, qué es OpenCode, alternativas, formatos de archivo

### Parte 1 — Primeros pasos

- Abriendo OpenCode, atajos de teclado, ejemplos prácticos (resumen, comparativa, fusión, formatos de salida), flujo de trabajo (Plan → Build → Tú), consejos y errores comunes

### Parte 2 — Un proyecto

- Ejemplo completo: proyecto de prácticas sobre tejidos animales (generación, borrador, modificación, inclusión de documentación)

### Parte 3 — Más potencia

- Más allá de la documentación, agentes, skills, MCP, Git

### Cierre

- Conclusiones, próximos pasos, referencias

## Contenido del proyecto

### Presentación activa

Archivo: `presentacion/v2.qmd`

~35 diapositivas en Quarto revealjs, autocontenidas. Tema oscuro institucional (#002028), tres partes + extras.

> La versión inicial (`presentacion/index.qmd`) se mantiene como referencia histórica.

### Análisis DAFO

Archivo: `dafo-presentacion.html`

Análisis de debilidades, amenazas, fortalezas y oportunidades de la presentación. Actualizado tras cada ronda de cambios.

### Notas de diseño

Archivo: `apuntesParaPresentacion.md`

Directrices de estilo visual, tono, audiencia y estructura para la presentación.

### Instrucciones del proyecto

Archivo: `AGENTS.md`

Comandos, estructura y convenciones para el desarrollo de la sesión con OpenCode.

### Guía de ejercicios

Archivo: `ejercicios/guia-ejercicios.qmd`

Guía paso a paso para los ejercicios prácticos de la sesión.
Incluye ejemplos, variantes y consejos.

### Ficha de referencia rápida

Archivo: `recursos/ficha-referencia.qmd`

Documento conciso para consultar después de la sesión. Incluye
estructura de peticiones, verbos útiles y recursos.

## Cursos de apoyo

Esta sesión se apoya en dos cursos existentes:

- **OpenCode 101** — Curso básico de 12 pasos para creadores de contenido
  [palazon.github.io/ocCursoIntro](https://palazon.github.io/ocCursoIntro/)

- **OpenCode 102** — Curso avanzado de 8 pasos (automatización, personalización)
  [palazon.github.io/ocCursoAvanzado](https://palazon.github.io/ocCursoAvanzado/)

## Requisitos para asistentes

- Portátil propio con batería cargada
- OpenCode instalado (TUI o Desktop App)
- Conexión a internet (wifi del aulario)

## Generar materiales

Para generar los materiales en formato HTML:

```bash
# Instalar Quarto (si no está instalado)
# https://quarto.org/docs/get-started/

# Generar presentación (activa)
quarto render presentacion/v2.qmd

# Generar guía de ejercicios
quarto render ejercicios/guia-ejercicios.qmd

# Generar ficha de referencia
quarto render recursos/ficha-referencia.qmd
```

## Licencia

Este material se distribuye bajo la licencia
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes compartirlo y adaptarlo, pero solo con fines no comerciales
y bajo la misma licencia.

---

*Sesión "OpenCode para gestión universitaria" · 2 de julio de 2026*
