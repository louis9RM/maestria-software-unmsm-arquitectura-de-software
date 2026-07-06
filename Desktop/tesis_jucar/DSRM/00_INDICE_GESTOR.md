ededo# ÍNDICE / GESTOR — Plantilla de Prompts DSRM
### Basado fielmente en: Johannesson, P. & Perjons, E. (2014), *An Introduction to Design Science*, Springer.

---

## 0. Qué es esto

Esta carpeta contiene una plantilla de prompts reutilizable para ejecutar una investigación completa siguiendo la metodología **Design Science Research Methodology (DSRM)** tal como la exponen Johannesson y Perjons en el libro `[P2]`. Está pensada para que la reutilices en **cualquier tesis, artículo o proyecto de investigación**, sin importar el tema: solo rellenas los marcadores `[ASÍ]` en cada prompt.

**Importante — precisión terminológica del libro (para que no haya confusión más adelante):**

El libro define en el **Capítulo 4** un "Method Framework for Design Science Research" compuesto por **exactamente cinco actividades** (Sect. 4.1):

1. Explicate Problem (Cap. 5)
2. Define Requirements (Cap. 6)
3. Design and Develop Artefact (Cap. 7)
4. Demonstrate Artefact (Cap. 8)
5. Evaluate Artefact (Cap. 9)

El **Capítulo 10** ("Communicate Artefact Knowledge") **no** aparece en la lista de las cinco actividades del framework (Sect. 4.1) — es un capítulo aparte, sobre cómo redactar y comunicar los resultados. Lo incluyo igualmente como **archivo 06**, porque es indispensable para escribir tu tesis/artículo, pero lo marco explícitamente como *complementario al framework*, no como un "sexto paso" oficial de la DSRM. Esta distinción es del libro, no una interpretación mía.

Archivos de esta carpeta:

```
DSRM/
 ├─ 00_INDICE_GESTOR.md          ← este archivo
 ├─ 01_Explicate_Problem.md       (Cap. 5 — Paso 1 del framework)
 ├─ 02_Define_Requirements.md     (Cap. 6 — Paso 2 del framework)
 ├─ 03_Design_Develop_Artefact.md (Cap. 7 — Paso 3 del framework)
 ├─ 04_Demonstrate_Artefact.md    (Cap. 8 — Paso 4 del framework)
 ├─ 05_Evaluate_Artefact.md       (Cap. 9 — Paso 5 del framework)
 └─ 06_Communicate_Knowledge.md   (Cap. 10 — complementario, no es "paso 6")
```

---

## 1. Orden y dependencias — lo que el libro realmente dice

Esto es crítico y muchas personas lo malinterpretan: el diagrama del framework (Fig. 4.1) **parece** secuencial porque cada actividad tiene una flecha de salida hacia la siguiente, pero el propio libro dedica el **Capítulo 11 entero** a aclarar que **esas flechas NO son un orden temporal obligatorio, sino relaciones lógicas de entrada/salida** (input-output), análogas a las "disciplinas" de RUP (Rational Unified Process) frente a sus "fases".

En la práctica esto significa:

- **No** es un modelo cascada (*waterfall*). El libro critica explícitamente ese modelo por ser inadecuado (Cap. 11.1).
- Puedes y **debes** iterar: volver de "Diseñar y Desarrollar" a "Definir Requisitos", o de "Evaluar" a "Explicitar el Problema", cuantas veces sea necesario.
- Cualquier actividad puede, en principio, recibir insumos de y producir salidas para cualquier otra actividad; el diagrama solo marca las relaciones más importantes (Sect. 4.1, última línea).
- Lo que sí es fijo son los **inputs y outputs que cada actividad exige como mínimo** (eso es lo que cada archivo de esta carpeta especifica en su sección "Insumos" y "Entregables").

**Cadena input→output "por defecto" (Fig. 4.1), a usar como punto de partida, no como camisa de fuerza:**

```
Problema inicial
   → [1. Explicate Problem]        → Problema explicitado (causas raíz)
   → [2. Define Requirements]      → Artefacto esbozado + Requisitos
   → [3. Design & Develop Artefact]→ Artefacto + conocimiento de diseño
   → [4. Demonstrate Artefact]     → Artefacto demostrado (1 caso)
   → [5. Evaluate Artefact]        → Artefacto evaluado
   → [Comunicar conocimiento]      → Tesis / artículo / paper
```

---

## 2. Cómo usar esta plantilla paso a paso

1. Abre `01_Explicate_Problem.md`. Rellena los marcadores del prompt con los datos de TU investigación (tema, problema inicial, práctica/contexto, stakeholders).
2. Pega el prompt completo a un asistente de IA (o úsalo tú mismo como checklist manual). El resultado debe ser el "Entregable" que ese archivo especifica: el problema explicitado con sus causas raíz.
3. Copia ese entregable como parte del insumo del prompt del archivo `02_Define_Requirements.md`.
4. Repite el proceso para los archivos 03, 04 y 05, siempre encadenando el entregable del paso anterior como insumo del siguiente.
5. Si en cualquier punto descubres que necesitas reformular el problema o los requisitos (esto es normal y esperado, ver Sect. 11.1), vuelve al archivo correspondiente y vuelve a ejecutar ese prompt con la nueva información. No pasa nada por "retroceder" — es lo que el libro llama trabajar de forma iterativa.
6. Cuando tengas los 5 entregables, usa `06_Communicate_Knowledge.md` para estructurar el capítulo de metodología / resultados de tu tesis o el paper, siguiendo la estructura de 7 partes que propone el Cap. 10.

---

## 3. Qué NO cubre esta plantilla (y por qué)

Para que la plantilla se mantenga fiel al libro y no se infle con contenido que tú no pediste, dejé fuera — deliberadamente — otros capítulos del libro que son **transversales** y no estructurados como "pasos":

- **Cap. 1-2** (qué es design science, tipos de conocimiento y de artefactos: construct/model/method/instantiation) — esto ya está resumido dentro de cada archivo donde aplica (p. ej. en el paso 2, al elegir el tipo de artefacto).
- **Cap. 3** (catálogo completo de estrategias y métodos de investigación: experimentos, encuestas, estudios de caso, etnografía, teoría fundamentada, investigación-acción, fenomenología, simulación, prueba matemática, más métodos de recolección y análisis de datos) — cada archivo de paso ya incluye, resumida y aplicada a ESE paso específico, la sección del libro que indica qué estrategias son más/menos apropiadas para él (Sect. 5.3, 6.3, 7.2, 9.5).
- **Cap. 12** (paradigmas de investigación: positivismo, interpretivismo, realismo crítico, teoría crítica) — relevante sobre todo para justificar metodológicamente tus elecciones de estrategias/métodos en el capítulo de metodología de la tesis.
- **Cap. 13** (ética en design science) — el libro da 6 principios éticos específicos para investigación en design science (Sect. 13.3) que aplican transversalmente a TODOS los pasos, no a uno en particular.

Si quieres, puedo crear archivos adicionales `07_Research_Paradigms.md` y `08_Ethics.md` con el mismo formato de prompt reutilizable — dímelo y los preparo con la misma fidelidad al libro.

---

## 4. Advertencias de fidelidad (cosas que decidí explícitamente, para que las revises)

Tal como pediste, aquí van los puntos donde tuve que tomar una decisión de diseño en vez de asumir silenciosamente:

1. **El libro no está escrito pensando en prompts de IA.** El contenido de "qué exige cada paso" es 100% del libro; el *formato* de prompt reutilizable con marcadores `[ASÍ]` es una construcción mía para cumplir tu pedido. Te lo señalo para que sepas dónde termina el libro y empieza la plantilla.
2. **Las "guidelines" (guías) de cada capítulo son listas de viñetas cualitativas en el libro**, no checklists numerados. Las convertí en checklists dentro de los prompts para que sean accionables, sin alterar su contenido.
3. **El diagrama de Ishikawa del Cap. 5 (Fig. 5.2)** usa categorías de un ejemplo genérico de manufactura ("People, Machines, Equipment, Environment, Management"). El libro NO exige esas categorías para todo dominio — es un ejemplo. En el prompt del paso 1 dejo esto explícito para que adaptes las categorías a tu propio dominio (p. ej., para un gemelo digital de sensor: podrían ser "Sensor físico, Modelo estadístico, Entorno de simulación, Datos, Validación").
4. **La estructura de 7 partes para papers de design science (Sect. 10.3)** es una propuesta del libro, y el propio libro aclara que "pueden ser útiles ciertas modificaciones" según el caso (p. ej. fusionar "Problem and Requirements" con "Artefact" si los requisitos ya son bien conocidos). Lo mantengo como estructura por defecto, señalando esa flexibilidad.
5. **Los "kernel theories" (teorías base)** que debes relacionar con tu artefacto (Sect. 4.3) no tienen un procedimiento fijo en el libro más allá de "relacionar con la base de conocimiento existente" — el prompt del paso 2 y 3 te pide identificarlas, pero la profundidad de esa búsqueda depende de tu criterio como investigador.

Nada de esto contradice al libro; son huecos de aplicación práctica que el libro deja abiertos y que yo hice explícitos en vez de rellenar por mi cuenta sin decírtelo.
