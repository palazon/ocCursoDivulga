# AGENTS.md

Sesión "OpenCode para gestión universitaria" — materiales en Quarto.

## Comandos

```bash
# Regenerar cualquier archivo individual
quarto render presentacion/v2.qmd
quarto render ejercicios/guia-ejercicios.qmd
quarto render recursos/opencode-guia-breve.qmd
quarto render recursos/ficha-referencia.qmd
```

No hay build system, tests, linter ni typecheck. Solo Quarto.

## Estructura

- `presentacion/v2.qmd` — Presentación principal (revealjs, tema oscuro institucional)
- `presentacion/index.qmd` — Versión inicial de la presentación (no usar, referencial)
- `ejercicios/guia-ejercicios.qmd` — Guía de ejercicios prácticos
- `recursos/opencode-guia-breve.qmd` — Guía breve de instalación y configuración
- `recursos/ficha-referencia.qmd` — Ficha de consulta rápida
- `apuntesParaPresentacion.md` — Notas y guía de estilo para la presentación

## Convenciones

- **Tono:** Coloquial pero preciso, tratamiento directo al oyente (no informático)
- **Palabras técnicas:** Incluir enlace a documentación de OpenCode cuando aparezcan
- **Ejemplos:** Añadir planteamiento antes (¿qué necesitas? ¿para qué?) y reflexión después (¿qué ha funcionado?)
- **Fuentes:** Cabeceras 1.7em/1.6em, texto base 24px
- **Tema visual:** Fondo oscuro (#002028), texto blanco, acentos verdes (#52b788)

## Notas

- Los archivos HTML generados están en `.gitignore` — no commitearlos
- Las carpetas `*_files/` también están excluidas
- La presentación v2 es la activa; index.qmd es la versión original de referencia
