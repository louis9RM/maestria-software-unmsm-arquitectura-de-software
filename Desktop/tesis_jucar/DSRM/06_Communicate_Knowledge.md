# COMPLEMENTARIO — Communicate Artefact Knowledge (Comunicar el Conocimiento del Artefacto)

> Fuente: Johannesson & Perjons (2014), *An Introduction to Design Science*, **Capítulo 10** (pp. 151-156).

> ⚠️ **Nota de fidelidad importante:** este archivo **no corresponde a un "sexto paso" del Method Framework**. El framework oficial (Sect. 4.1) tiene exactamente 5 actividades (Explicate Problem → Define Requirements → Design and Develop Artefact → Demonstrate Artefact → Evaluate Artefact). El Capítulo 10 es un capítulo separado del libro sobre cómo **comunicar** los resultados de esas 5 actividades. Lo incluyo aquí porque es la pieza que necesitas para redactar tu tesis/artículo, pero quería dejarte explícito que el propio libro no lo llama "parte del framework".

---

## 1. Qué exige el libro en este capítulo

### 1.1 Comunicar a distintas audiencias (Sect. 10.1)

El libro distingue explícitamente cómo adaptar la comunicación según la audiencia:

- **Investigadores:** requieren rigor metodológico — describir bien la base de conocimiento (knowledge base), justificar la elección de estrategias/métodos de investigación, y detallar su aplicación (incluyendo validez y confiabilidad).
- **Practicantes orientados a tecnología** (ingenieros): les interesan los detalles de la **estructura** del artefacto (componentes y relaciones), para poder construirlo/implementarlo o seguir desarrollándolo.
- **Practicantes orientados a gestión** (managers): les interesa el **problema** que resuelve, los **beneficios**, la **facilidad de uso**, y los **efectos globales** (ej. eficiencia, agilidad organizacional) — la estructura interna les interesa menos.
- **Público general:** el foco principal son los **efectos**, incluidas las consecuencias éticas y sociales.

### 1.2 Canales de comunicación

- Comunidades académicas: journals, conferencias, workshops (los workshops aceptan trabajo inmaduro para retroalimentación; los journals exigen trabajo maduro con evaluación rigurosa).
- Comunidades de práctica: ferias comerciales, *white papers*, artículos de revista, blogs.

### 1.3 Estructura IMRAD (base general de papers empíricos, Sect. 10.2)

Introducción, Método, Resultados, Discusión — estructura estándar en ciencias naturales y sociales.

### 1.4 Estructura adaptada para papers/tesis de Design Science (Sect. 10.3) — 7 PARTES

Esta es la estructura que el libro propone específicamente para comunicar investigación en design science (adaptando IMRAD):

1. **Introduction (Introducción):** contexto general del área, el problema práctico y la(s) práctica(s) donde aparece, su significancia, resumen de investigación existente y vacíos de conocimiento, preguntas/metas de investigación, tipo de artefacto desarrollado/evaluado, soluciones similares o alternativas existentes, teorías base ("kernel theories") usadas, resumen de estrategias/métodos de investigación usados, resumen de las contribuciones y su significancia, y estructura del resto del documento. Opcionalmente, un ejemplo concreto que ilustre la relevancia del problema.

2. **Method (Método):** visión general del uso de estrategias y métodos de investigación en el estudio: estrategias de investigación, métodos de recolección y análisis de datos, justificación de los métodos elegidos, y discusión de ética de investigación.

3. **Problem and Requirements (Problema y Requisitos):** descripción y análisis elaborado del problema práctico (incluyendo, si aplica, el análisis de causas raíz), y definición de los requisitos del artefacto, justificados a partir del análisis del problema. Puede describir también el proceso de análisis del problema y elicitación de requisitos (aplicación de métodos, uso de la base de conocimiento).

4. **Artefact (Artefacto):** descripción del artefacto — estructura, comportamiento y función, idealmente con ejemplos. Puede describir el proceso de desarrollo (alternativas de diseño, design rationale, base de conocimiento usada). **Suele ser la parte principal** de un paper de design science.

5. **Evaluation (Evaluación):** descripción de cómo se evaluó el artefacto — estrategia de evaluación y proceso, especialmente cómo se aplicaron las estrategias/métodos de investigación elegidos. A veces, si el artefacto es muy innovador, esta parte puede ser más breve, o incluso limitarse a describir una demostración (Paso 4).

6. **Discussion (Discusión):** reflexión sobre la investigación y sus contribuciones — limitaciones del estudio, novedad y valor del artefacto comparado con existentes, significancia práctica y teórica de las contribuciones, y discusión de aspectos éticos del uso del artefacto. Puede sugerir áreas de investigación futura. Opcionalmente, reflexión sobre el uso del método framework de design science mismo.

7. **Conclusion (Conclusión):** cierra el documento mostrando cómo se respondieron las preguntas de investigación (o se lograron las metas de investigación).

> **Flexibilidad reconocida por el propio libro:** la Introducción a veces se divide en dos partes (agregando un "extended background" o "literature review") si la base de conocimiento es muy amplia o la práctica es compleja/poco familiar. La parte "Problem and Requirements" a veces se fusiona con "Artefact" cuando los requisitos ya son bien conocidos y no requirieron un proceso de elicitación propio. Los límites entre "Problem and Requirements", "Artefact" y "Evaluation" pueden ser difusos debido a la naturaleza iterativa del proceso de diseño (ver Cap. 11 sobre órdenes lógicos vs. temporales).

---

## 2. Guía de mapeo: tus 5 entregables (Pasos 1-5) → las 7 partes del documento

| Parte del documento | Entregable(s) DSRM que la alimentan |
|---|---|
| 1. Introduction | Resumen de Paso 1 (problema + justificación) + contexto general + antecedentes |
| 2. Method | Estrategias/métodos que elegiste en cada paso (Sect. 5.3, 6.3, 9.5 de tus prompts) |
| 3. Problem and Requirements | Entregable completo del Paso 1 + entregable completo del Paso 2 |
| 4. Artefact | Entregable completo del Paso 3 (y, si aplica, del Paso 4 como ilustración) |
| 5. Evaluation | Entregable completo del Paso 4 (demostración) + entregable completo del Paso 5 (evaluación) |
| 6. Discussion | Limitaciones detectadas en Pasos 1-5, comparación con artefactos existentes (Paso 5), consecuencias éticas |
| 7. Conclusion | Síntesis de si el problema del Paso 1 quedó resuelto según la evaluación del Paso 5 |

---

## 🔧 PROMPT REUTILIZABLE — Redactar el documento siguiendo la estructura de Design Science

```
Actúa como redactor científico aplicando la estructura para papers/tesis de Design Science propuesta por Johannesson & Perjons (2014, Cap. 10, Sect. 10.3), que adapta la estructura IMRAD a investigación de design science.

TENGO LOS SIGUIENTES ENTREGABLES DE MI INVESTIGACIÓN (DSRM):

PASO 1 — Problema explicitado:
[ENTREGABLE_PASO_1]

PASO 2 — Artefacto esbozado + requisitos:
[ENTREGABLE_PASO_2]

PASO 3 — Artefacto diseñado y desarrollado + design rationale:
[ENTREGABLE_PASO_3]

PASO 4 — Artefacto demostrado:
[ENTREGABLE_PASO_4]

PASO 5 — Artefacto evaluado:
[ENTREGABLE_PASO_5]

AUDIENCIA PRINCIPAL de este documento (elige una o combina, según Sect. 10.1 del libro): [AUDIENCIA: investigadores / practicantes orientados a tecnología / practicantes orientados a gestión / público general / tribunal de tesis]

TIPO DE DOCUMENTO: [TIPO_DE_DOCUMENTO: capítulo de tesis / artículo para conferencia / artículo para journal / resumen ejecutivo]

TAREA: Redacta el documento siguiendo la estructura de 7 partes del libro, adaptando el nivel de detalle a la audiencia indicada:

1. INTRODUCTION: contexto del área, problema y práctica donde aparece, significancia, vacíos de conocimiento (a partir del Paso 1), tipo de artefacto y soluciones alternativas existentes (a partir del Paso 2 y 3), teorías base usadas, resumen de métodos usados en todo el proyecto, resumen de contribuciones, estructura del documento.

2. METHOD: resume las estrategias y métodos de investigación usados en cada paso (problema, requisitos, evaluación), justifícalos, y menciona brevemente consideraciones éticas si las hay.

3. PROBLEM AND REQUIREMENTS: integra el Paso 1 y Paso 2 en una narrativa coherente (no los pegues tal cual, redáctalos como prosa académica), incluyendo el análisis de causas raíz y la tabla de requisitos.

4. ARTEFACT: integra el Paso 3 (y usa el Paso 4 como ejemplo ilustrativo dentro de esta sección si el artefacto se explica mejor con un caso). Explica estructura, función, comportamiento, con ejemplos concretos.

5. EVALUATION: integra el Paso 4 y Paso 5 — cómo se demostró y evaluó el artefacto, resultados, y honestidad sobre las limitaciones del tipo de evaluación usado (ex ante/ex post, artificial/naturalista).

6. DISCUSSION: limitaciones del estudio, comparación con soluciones existentes, significancia práctica/teórica, aspectos éticos, líneas de trabajo futuro.

7. CONCLUSION: cierra respondiendo explícitamente si el problema planteado en la Introducción fue resuelto y en qué medida, según la evidencia del paso de evaluación.

Indícame si alguna de las 7 partes necesitaría más información de la que te di para completarse con rigor académico, en vez de rellenar huecos por tu cuenta.
```

## Marcadores a completar

- `[ENTREGABLE_PASO_1]` … `[ENTREGABLE_PASO_5]`: pega los resultados completos de cada prompt anterior.
- `[AUDIENCIA]`: para quién escribes principalmente (esto cambia el énfasis: más estructura técnica vs. más beneficios/efectos).
- `[TIPO_DE_DOCUMENTO]`: define el nivel de extensión y formalidad esperado.
