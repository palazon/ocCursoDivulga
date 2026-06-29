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

Dar a conocer el potencial de OpenCode como asistente para tareas
académicas y de gestión universitaria, usando programación con
lenguaje natural.

## Estructura de la sesión

### Bloque 1 — Presentación teórica (60 min)

1. Introducción y contexto (10 min)
2. Casos de uso en gestión universitaria (20 min)
3. Demostración en vivo (20 min)
4. Recursos disponibles (10 min)

### Bloque 2 — Ejercicios prácticos (60 min)

1. Preparación del entorno (10 min)
2. Ejercicio guiado 1 (15 min)
3. Ejercicio guiado 2 (15 min)
4. Ejercicio libre (15 min)
5. Cierre y próximos pasos (5 min)

## Contenido del proyecto

### Presentación

Archivo: `presentacion/index.qmd`

Diapositivas para la parte teórica de la sesión. Formato Quarto
revealjs, compatible con navegadores web.

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
- OpenCode instalado (versión GUI)
- Conexión a internet (wifi del aulario)

## Generar materiales

Para generar los materiales en formato HTML:

```bash
# Instalar Quarto (si no está instalado)
# https://quarto.org/docs/get-started/

# Generar presentación
quarto render presentacion/index.qmd

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
