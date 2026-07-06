# PASO 3 — Design and Develop Artefact (Diseñar y Desarrollar el Artefacto)

> Fuente: Johannesson & Perjons (2014), *An Introduction to Design Science*, **Capítulo 7** (pp. 117-131).
> Tercera actividad del Method Framework for Design Science Research (Sect. 4.1).

---

## 1. Qué exige el libro en este paso

Esta actividad, a diferencia de las demás, no se formula como pregunta sino como **tarea** (textual del libro, Cap. 7):
> "Create an artefact that addresses the explicated problem and fulfils the defined requirements."
> ("Crear un artefacto que aborde el problema explicitado y cumpla los requisitos definidos.")

**Tipo de conocimiento producido:** principalmente *prescriptivo* (embebido en el artefacto creado) + conocimiento *descriptivo* sobre las decisiones de diseño y su justificación (el "*design rationale*").

**Nota importante del libro:** a diferencia de los otros pasos, aquí **los métodos y estrategias de investigación son secundarios** — lo prioritario es producir el artefacto, usando cualquier enfoque creativo que funcione (Sect. 7.2). Esto no significa que no debas documentar rigurosamente el proceso.

---

## 2. Sub-actividades obligatorias (Sect. 7.1)

1. **Imagine and Brainstorm (Imaginar y generar ideas, 7.1.1):** generar el mayor número de ideas alternativas (*pensamiento divergente*). Técnicas mencionadas explícitamente por el libro:
   - **Empathetic thinking** (pensamiento empático): intentar ver el mundo desde los ojos de los usuarios, como haría un antropólogo.
   - **Lateral thinking** de de Bono: generación aleatoria, generación provocativa (pensamiento deseoso, exageración, cuestionar verdades aceptadas), técnica de los "seis sombreros para pensar".
   - **Brainstorming en grupo:** producir muchas ideas sin criticar, luego consolidar y priorizar. El libro advierte que la presión de tiempo, el liderazgo directivo y las normas de grupo (p. ej. "no cuestiones a tu jefe") pueden inhibir la creatividad.
   - **Generación individual antes de grupal**: la evidencia citada (Isaksen 1998; Diehl & Stroebe 1987) muestra que combinar generación individual + grupal suele superar al brainstorming puramente grupal.
   - **Método 6-3-5 brainwriting**: 6 participantes, 3 ideas cada uno, 5 minutos, en 6 rondas.
   - **Lead users / user innovation**: usuarios con conocimiento profundo y alto interés pueden generar ideas de mejora por sí mismos.
   - **Modelo de Wallas** (proceso creativo individual): preparación → incubación → iluminación → verificación.
   - **Clasificación de métodos de generación de ideas** (Shah et al. 2000): germinales (desde cero, ej. brainstorming), transformacionales (modificando ideas existentes, ej. generación aleatoria), progresivos (iterando el mismo paso, ej. 6-3-5), organizacionales (agrupando ideas ya generadas).

2. **Assess and Select (Evaluar y seleccionar, 7.1.2):** *pensamiento convergente* — reducir el espacio de soluciones posibles guiado por los requisitos del Paso 2. El libro describe 3 modelos de toma de decisiones (de la sociología/teoría de organizaciones), útiles tanto para describir cómo se decide como para guiar cómo debería decidirse:
   - **Rational decision-making**: evaluar en profundidad todas las ideas relevantes para hallar la óptima.
   - **Bounded rationality**: detener la búsqueda al encontrar una idea "suficientemente buena".
   - **Garbage can model**: decisiones ad hoc, emparejando problemas y soluciones disponibles sin mucha discusión.
   También advierte sobre sesgos cognitivos a evitar: **anchor bias** (anclarse en la primera idea), **confirmation bias** (favorecer ideas que confirman creencias previas), **sunk cost bias** (elegir ideas que justifiquen decisiones pasadas).

3. **Sketch and Build (Bosquejar y construir, 7.1.3):** primero un **bosquejo (sketch)** de funciones y estructura del artefacto:
   - Para funciones: diagramas de casos de uso, descripciones de casos de uso, historias de usuario (*user stories*), *storyboarding*.
   - Para estructura: para un método, las partes son actividades/tareas con su orden; para un modelo/instanciación, son módulos/componentes.
   - Luego, opcionalmente, un **prototipo** (borrador temprano enfocado en algún aspecto: dibujo en papel, modelo físico, aplicación de software parcial) antes del artefacto final.
   - Instrumentos de apoyo: **pair design** (dos diseñadores trabajando juntos, análogo a *pair programming*), **walk-through** (revisión por pares guiada), **user-centred design** (retroalimentación constante de usuarios reales).
   - Reutilizar y adaptar soluciones existentes (estudiar literatura y artefactos previos) combinado con invención de elementos nuevos.

4. **Justify and Reflect (Justificar y reflexionar, 7.1.4):**
   - Documentar el **design rationale**: lista de decisiones de diseño tomadas, alternativas consideradas, y argumentos que llevaron a cada decisión. El libro lo señala como **uno de los resultados más valiosos** de un proyecto de design science, útil para evitar callejones sin salida en trabajo futuro.
   - Reflexionar sobre el propio proceso de trabajo (aprendizaje individual/organizacional), especialmente relevante en métodos ágiles.

> **Nota:** el libro reconoce que "diseño" (sketch) y "desarrollo" (build) a veces se usan de forma ambigua en la literatura; en este capítulo, *sketch* = diseño, *build* = desarrollo, pero las dos primeras sub-actividades (Imagine/Brainstorm y Assess/Select) también son, en rigor, parte del diseño.

---

## 3. Insumos (input) para este paso

- El **esbozo del artefacto + lista de requisitos** (Paso 2).

## 4. Entregable (output) de este paso

El **artefacto** (construido, al menos como prototipo) + el **conocimiento sobre el artefacto**: decisiones de diseño tomadas, su justificación (*design rationale*), y en qué se diferencia de soluciones existentes.

## 5. Guías explícitas del libro para este paso (Sect. 7.3)

- Describir claramente cada componente del artefacto (función y estructura).
- Justificar cada componente (qué requisito atiende).
- Describir cómo se usará el artefacto en su práctica prevista.
- Aclarar la originalidad: en qué difiere de soluciones existentes (función y estructura).
- Especificar las fuentes del diseño (literatura y stakeholders que inspiraron componentes).
- Describir cómo se diseñó y desarrolló el artefacto (participación de stakeholders, revisión de soluciones existentes y literatura).

## 6. Criterio de salida — cuándo pasar al Paso 4

Cuando tengas un artefacto (aunque sea un prototipo) construido, con su design rationale documentado y trazable a los requisitos del Paso 2.

---

## 🔧 PROMPT REUTILIZABLE — Diseñar y Desarrollar el Artefacto

```
Actúa como investigador aplicando la metodología Design Science Research (Johannesson & Perjons, 2014) para la actividad "Design and Develop Artefact" (Cap. 7 del libro).

ARTEFACTO Y REQUISITOS (entregable del Paso 2, o descríbelos si aún no los tienes formalizados):
[TIPO_DE_ARTEFACTO_Y_REQUISITOS]

CONTEXTO ADICIONAL:
- Teorías, técnicas o marcos que podrían servir de base ("kernel theories") para el diseño: [TEORIAS_BASE]
- Soluciones existentes que puedo usar como referencia o punto de partida: [SOLUCIONES_REFERENCIA]
- Herramientas/tecnologías que usaré para construir el artefacto: [HERRAMIENTAS_TECNOLOGIA]
- Recursos con los que cuento para brainstorming/revisión (¿trabajo solo, con asesor, con otros investigadores?): [RECURSOS_HUMANOS]

TAREA — Ejecuta las 4 sub-actividades de "Design and Develop Artefact":

1) IMAGINE AND BRAINSTORM: Genera al menos 4-6 ideas/alternativas de diseño distintas para cumplir los requisitos dados. Usa explícitamente al menos dos de estas técnicas del libro para diversificar las ideas: pensamiento empático (ponte en el lugar del usuario/practicante final), pensamiento lateral (genera una idea "provocativa" cuestionando un supuesto dado por sentado del enfoque estándar), y clasifica cada idea generada según si es germinal, transformacional, progresiva u organizacional.

2) ASSESS AND SELECT: Evalúa las alternativas generadas contra los requisitos (funcionales y no funcionales) del Paso 2. Indica qué modelo de decisión estás usando implícitamente (racional, racionalidad limitada, o "garbage can") y por qué es razonable dado mi contexto. Señala explícitamente si alguna alternativa corre el riesgo de sesgo de anclaje, confirmación o costos hundidos, y justifica por qué la descartas o la mantienes a pesar de ese riesgo. Selecciona y justifica la(s) alternativa(s) final(es).

3) SKETCH AND BUILD: Para la alternativa seleccionada, entrega:
   - Un bosquejo funcional (qué hace el artefacto, para quién, cómo se usa) en forma de casos de uso o historias de usuario, según convenga al tipo de artefacto.
   - Un bosquejo estructural (arquitectura/componentes/módulos y sus relaciones, o pasos/actividades si es un método).
   - Indicación de qué parte de esto amerita un prototipo y de qué aspecto se debería enfocar ese prototipo (ej. viabilidad técnica, usabilidad, precisión).

4) JUSTIFY AND REFLECT: Redacta el "design rationale": una tabla de decisiones de diseño tomadas, alternativas descartadas, y el argumento de por qué se tomó cada decisión. Añade una reflexión breve sobre qué se aprendió del proceso y qué se haría distinto en una siguiente iteración.

FORMATO DE SALIDA:
- Alternativas generadas (con su clasificación de técnica de generación de ideas)
- Alternativa(s) seleccionada(s) + justificación de la decisión
- Bosquejo funcional
- Bosquejo estructural
- Tabla de design rationale (Decisión | Alternativas consideradas | Justificación | Requisito(s) que cumple)
- Explicación de en qué se diferencia esta propuesta de las soluciones existentes que mencioné

Si necesitas conocimiento técnico especializado que no tengo (p. ej. detalles de una teoría o tecnología específica) para completar el diseño con rigor, dime exactamente qué información falta en vez de inventarla.
```

## Marcadores a completar

- `[TIPO_DE_ARTEFACTO_Y_REQUISITOS]`: pega el entregable completo del Paso 2.
- `[TEORIAS_BASE]`: teorías/modelos que fundamentan tu diseño (ej. "modelos de regresión lineal múltiple, teoría de ruido de sensores LiDAR, principios de gemelos digitales").
- `[SOLUCIONES_REFERENCIA]`: papers/proyectos similares (los mismos del Paso 2 u otros más técnicos).
- `[HERRAMIENTAS_TECNOLOGIA]`: p. ej. "Python, scikit-learn, NVIDIA Isaac Sim, datos del datasheet SLAMTEC RPLiDAR A1M8".
- `[RECURSOS_HUMANOS]`: solo, con asesor, con equipo, etc. — influye en si recomendar brainstorming grupal o individual.
