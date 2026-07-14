# AGENTS.md

Sesión "OpenCode para gestión universitaria" — presentación RevealJS en Quarto.

## Comandos

```bash
quarto render 100-oc-divulga.qmd
```

No hay build system, tests, linter ni typecheck. Solo Quarto.

## Estructura

- `100-oc-divulga.qmd` — Fuente de la presentación (~42 slides, revealjs)
- `100-oc-divulga.html` / `dafo-presentacion.html` — Salida renderizada (trackeada en git)
- `AGENTS.md`, `README.md`, `LICENSE`, `VERSION` — Metadatos del proyecto
- `docs/` — Documentos de apoyo y análisis
  - `bases-cambio-modelo.{qmd,html,pdf}` — Ensayo del modelo de texto plano + agentes
  - `diagnostico-usuario.{qmd,html}` — Diagnóstico del perfil de usuario
  - `faq-cambio-modelo.{qmd,html,pdf}` — Preguntas frecuentes
  - `analisis-plantilla-ineficiente.qmd` / `analisis-plantillas-universitarias.qmd` — Análisis de plantillas
  - `custom.css` / `cosmo-custom.scss` — Estilos compartidos

## Convenciones

- **Tono:** Coloquial pero preciso, tratamiento directo al oyente (no informático)
- **Palabras técnicas:** Incluir enlace a documentación de OpenCode cuando aparezcan
- **Ejemplos:** Añadir planteamiento antes (¿qué necesitas? ¿para qué?) y reflexión después (¿qué ha funcionado?)
- **Tema visual:** Fondo oscuro `#002028`, texto blanco, acentos `#52b788` — definido inline en cabecera YAML del `.qmd`
- **Fuentes:** `--r-heading1-size: 2.04em`, `--r-heading2-size: 1.92em`, `--r-main-font-size: 29px`
- **Enlaces externos:** Todos usan `{target="_blank"}` para abrir en nueva pestaña
- **Notas al margen:** Preferir `<aside>` frente a footnotes `[^...]` para anotaciones
- **Renderizado:** `self-contained: true` — todo el output va a un HTML autocontenido

## Notas

- No hay `.gitignore`; los HTML generados están trackeados en git
- No hay `_quarto.yml`; toda la configuración está en la cabecera YAML de `100-oc-divulga.qmd`
