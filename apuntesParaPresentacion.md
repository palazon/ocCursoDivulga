La presentación servirá de apoyo y guía a una sesión eminentemente práctia y experimental.
Debe marca los principales hitos y conceptos que se despelgarán a reglón seguido con un ejemplo práctico.
Las transparencias deben incluir cuando aparezcan palabras técnicas un enlace para aclarar aspectos previos necesarios para una compresión completa
El debe ser coloquial pero precisa con temperatura 0.3
La audiencia no está habituada al texto plano ni a markdown, incluso les disgusta (se puede bromear con ello).
El nivel de la audiencia es de graduados o con formación universitaria, pero no informáticos.

el tratamiento es directo como si el material estuviese dirigido personalmente a oyente.
si el material lo creas como presentación reveljs, con tamaños de letra adeucados, y cabeceras con fuente no muy grande
Resalta el valor de la experimentación, ensaya con ejemplos simples para poder verificar la adecuación del procedimiento, con partes no con todo el material disponible, ...

Que puedo hacer con una navaja suiza de 1000 herramientas     frente a    qué quiero hacer

En los ejemplos añade, un breve planteamiento y preguntas generales a plantearse antes de empezar
y para después. Sugerencias para el proceso.

Cuidado con los tópicos, opencode es para programadores, markdown es para documentos técnicos, html para publicar en la red, ...

Habría tres partes, 

## Introducción

#### ¿Por qué este curso? Para presentar los cursos disponibles.

Naturaleza de esos cursos

Son cursos cola
- Cola: **c**urso **o**n **l**ine **a**utónomo
- Cola: Apéndice posterior del cuerpo de muchos animales, situado en la terminación del tronco.
- Cola: Sustancia adhesiva, generalmente líquida o pastosa, que se usa para unir objetos.
- Refrescante Aprendizaje Básico Online 

### Para quién el curso

Por qué y para quién es este taller: para aquellos que pasan la vida creando contenidos, reutilizando información, cambiando formatos, organizando proyecto personales y grupales, revisando materiales, corrigiendo documentación.

### Naturaleza de los problemas

Nuestros enemigos: el tiempo y los sesgos




#### ¿qué es opencode? según opencode

| Aspecto | Descripción |
|---|---|
| ¿Qué es? | Agente de IA de código abierto para escribir código en terminal, IDE o escritorio |
| Licencia | Open source (160K ★ en GitHub, 900+ contribuidores) |
| Uso | 7.5M de desarrolladores/mes |
| Modelos | Gratis incluidos, o conecta cualquier proveedor (Claude, GPT, Gemini, etc.) |
| Formatos | CLI, app de escritorio (beta), extensión IDE |
| Características | Multi-sesión, LSP automático, enlaces compartibles, 75+ proveedores de LLM |
| Privacidad | No almacena código ni contexto del usuario |
| Precio | Gratuito (con opción Zen para modelos optimizados) |

#### Pero soy creador de documentación no programador

| Aspecto | Descripción |
|---|---|
| ¿Qué es? | Sistema de documentación científica y técnica basado en Pandoc |
| Licencia | Open source (MIT) |
| Uso | Científicos, documentadores, creadores de informes y libros |
| Formatos de salida | HTML, PDF, DOCX, ePub, Reveal.js, Typst, más |
| Características | Markdown ejecutable, cross-references, citas, diagramas (Mermaid), extensiones |
| Privacidad | Sin telemetría. Renderizado 100% local |
| Precio | Gratuito |

#### ¿Alternativas a opencode? 
 
> ¿Qué alternativas hay a opencode?


#### Más sesgos

¿Qué tipo de ficheros podemos manejar y cuando usarlos?

* docx/odt
* html
* pdf
* markdow

### Manos a la obra

Más allá de un chateo pero con aspecto de chat vitaminado

Vamos a utilizar la *Desktop App* (Beta)  
(App nativa con GUI para macOS, Windows, Linux)

1. Área de conversación (panel principal)
1. *Input / prompt* (línea inferior):
1. Barra de estado, abajo a la izquierda 
Modo actual: Plan (solo planea, no edita) o Build (puede hacer cambios)
Modelo activo (ej. deepseek-v4-flash-free)
Proveedor configurado
Indicador de sesión: Múltiples sesiones pueden coexistir; se ven en /sessions.

* Ventana de respuesta
* Ventana de petición
* 
* Barra lateral de *Revisión*


## Primera parte  

Para ver algunos ejemplos básicos y el flujo de trabajo.
Antes de iniciar el trabajo

### Primer ejemplo

#### Unas preguntas

* *Biología* ¿qués biología?

La Wikipedia es una interesante fuente de información.

- ¿Qué opinión te merece?
- ¿Algún incoveniente?
- ¿Hay homogeneídad entre los diversos idiomas?

#### Usando OpenCode

Dentro de opencode

> Hola

> Dame un resumen de la entrada en Wikipedia de *Biología*. 

> Dame un resumen conceptual.

> Dame breve texto divulgativo sobre el concepto.

Flujo de trabajo

1. Entrada y salida de la herramienta
2. *Propmts*, uso de `Plain` y `Bluild`
3. Salida

#### Continuando con el uso

No insistiremos en los detalles de la interfaz, los justos para emplezar.

TODO: incluir las cuestionas básicas de la interfaz gráfica

¿Como retomar las sesiones de opencode?

> Compara la entrada de Biología en la Wikipedia en castellano con la inglesa.

Pero sobretodo insistiendo o, mejor, preparando para un
flujo de trabajo adecuado.

#### Fusión de documentos

> Dame una nueva versión que incluya la entrada en castellano y en inglés

#### Resultados: tipos y formatos 

> Presentación para 30 min (divulgación, aula de mayores) 

> PowerPoint — generado (.pptx)

> Versión en Quarto (.qmd) 
 

### ¿Paso a paso o completo?

Estrategia:

* Una petición global

* Desarrollo paso a paso

¿Pros? ¿Contra?

<!--
 1. Resumen de la entrada de Wikipedia para biología
 2. Resumen conceptual
 3. Presentación para 30 min (divulgación, aula de mayores) — estructura
 4. PowerPoint — generado (.pptx)
 5. Versión en Quarto (.qmd) — generada
 6. Esquema con TikZ — generado (.tex + .pdf)
 7. Versión del esquema en Mermaid — generada (.mmd + .svg)
 8. Comparativa entradas español vs inglés
 9. Fusión de ambas entradas en .docx
10. Fusión en Quarto renderizada a PDF — generado (.qmd + .pdf)
-->

#### Una reflexión

Es importante insistir en que primero pensamos que quermos,
como lo queremos, para quién lo queremos, ... todo esto
en un documento de trabajo.

## Consejos para peticiones efectivas

### Estructura de una buena petición

1. **Acción:** ¿Qué quieres que haga OpenCode?
   - "Crea", "Redacta", "Revisa", "Reestructura", "Traduce"

2. **Contexto:** ¿Para qué es? ¿A quién va dirigido?
   - "Para un acta de departamento", "Para un correo formal"

3. **Formato:** ¿Qué estructura debe tener?
   - "Con introducción, desarrollo y conclusiones"
   - "En formato de tabla"

4. **Ejemplos:** Si tienes algo similar, inclúyelo
   - "Al estilo de este otro documento ..."

# Errores comunes (y cómo evitarlos)

::: {.smaller}
| Error | Solución |
|-------|----------|
| Petición demasiado vaga | Sé más específico en tu petición |
| No incluir contexto | Añade información relevante |
| Esperar perfection la 1ª vez | Itera y pide ajustes |
| No revisar el resultado | Siempre lee y verifica lo generado |
| Copiar sin leer | Entiende lo que OpenCode produce |
:::


### Segunda parte

Aprovecharemos los ejemplos para ver los dos agentes,
la importacia de usar cada uno en su momento.
La creación del contenido en local, y por tanto 
la posibilidad de editar y manipular los ficheros y documentos.

/init

Mostrar como opencode resuelve distintas
situaciones habituales.
Como modificar algún texto y que se haga
una puesta en común con otros
Hablar de agentes, con un par de ejemplos

Ver el potencia de generación de html vs pdf vs office

Una rúbrica, un dafo de la rúbrica y una corrección con la rúbrica.
Preparación de proyecto para un minicurso sobre ...

* Tercera:

Como hacer recordar a opencode lo que queremos y nos gusta.
Más ejemplos, un skill sencillo.

Un poco sobre modelos, ... y todo los demás 

