# Cómo se hizo: Guía breve de OpenCode 2026

## Documento de partida

Se partió del tutorial "Tutorial de OpenCode 2026: Guía completa de instalación,
configuración y ajustes" de NxCode Team (enero 2026).

URL: https://www.nxcode.io/es/resources/news/opencode-tutorial-2026

## Proceso

1. **Revisión crítica:** se identificaron erratas, sesgos comerciales (promoción de
   NxCode), jerga técnica innecesaria y ejemplos inadecuados para el público objetivo
   (generadores de contenido, no programadores).

2. **Reescritura iterativa:** se reformularon las secciones eliminando referencias a
   editores específicos, adaptando los ejemplos a contextos de gestión documental y
   docencia, y verificando los atajos de teclado y comandos contra la documentación
   oficial de OpenCode.

3. **Correcciones factuales:**
   - Corregido `opencode -p` por `opencode run` (modo no interactivo)
   - Verificados los atajos `Cmd/Ctrl+Esc` (conflictos en Windows y Xfce4)
   - Confirmado que OpenCode viene con modelo Zen predefinido (no pide elegir al iniciar)

4. **Formato:** generación del HTML final con Quarto.

## Herramientas

- OpenCode (modelo big-pickle) — redacción y revisión
- Quarto — generación del HTML
