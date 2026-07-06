# PASO 4 — Demonstrate Artefact (Demostrar el Artefacto)

> Fuente: Johannesson & Perjons (2014), *An Introduction to Design Science*, **Capítulo 8** (pp. 133-136).
> Cuarta actividad del Method Framework for Design Science Research (Sect. 4.1).

---

## 1. Qué exige el libro en este paso

**Pregunta que debe responder esta actividad (textual del libro, Cap. 8):**
> "How can the developed artefact be used to address the explicated problem in one case?"
> ("¿Cómo puede usarse el artefacto desarrollado para abordar el problema explicitado en un caso?")

**Tipo de conocimiento producido:** principalmente *descriptivo* (cómo funciona el artefacto en una situación), y a veces *explicativo* (por qué funciona).

**Qué es una demostración, según el libro:** mostrar que el artefacto puede, de hecho, resolver algún aspecto del problema en **un caso ilustrativo o real** ("*proof of concept*"). El libro es explícito en algo importante: **la demostración es una forma "débil" de evaluación** — no reemplaza al Paso 5 (Evaluate Artefact), pero es útil porque (a) da un primer indicio de que el artefacto sí funciona en al menos un caso, y (b) permite comunicar la idea del artefacto de forma vívida y convincente.

---

## 2. Sub-actividades obligatorias (Sect. 8.1)

1. **Choose or Design Case (Elegir o diseñar un caso):** el caso puede ser:
   - **Ficticio**, diseñado por los propios investigadores (útil para poner a prueba el artefacto bajo condiciones extremas específicas).
   - Un **caso documentado en la literatura**.
   - Un **caso real**.
   - Una combinación de estos.
   El libro señala el trade-off: casos reales dan mejor validez externa; casos ficticios permiten diseñar deliberadamente condiciones desafiantes.

2. **Apply Artefact (Aplicar el artefacto):** usar el artefacto en el caso elegido, documentando el resultado de la aplicación.

---

## 3. Insumos (input) para este paso

- El **artefacto** desarrollado en el Paso 3 (al menos como prototipo funcional).

## 4. Entregable (output) de este paso

Un **"artefacto demostrado"**: evidencia de que el artefacto funciona en al menos un caso concreto, con la documentación de ese caso y de los resultados obtenidos al aplicarlo.

## 5. Recursos necesarios (Sect. 8.2)

Acceso y conocimiento sobre el caso elegido (sea ficticio, documentado, o real).

## 6. Estrategias de investigación sugeridas para ESTE paso (Sect. 8.3)

- **Investigación-acción** y **estudio de caso** son elecciones naturales cuando se usa un caso real.
- **Experimentos** son útiles tanto para casos ficticios como reales.

## 7. Guías explícitas del libro para este paso (Sect. 8.4)

- Justificar la elección del caso: explicar por qué es representativo del problema y suficientemente desafiante para ofrecer una prueba adecuada.
- Aclarar cuánto del artefacto se está probando: describir explícitamente qué componentes del artefacto se usaron realmente en la demostración (no siempre se prueba el artefacto al 100%).

## 8. Criterio de salida — cuándo pasar al Paso 5

Cuando tengas al menos un caso documentado donde el artefacto fue aplicado con éxito razonable, dejando claro qué proporción/componentes del artefacto fueron efectivamente puestos a prueba.

---

## 🔧 PROMPT REUTILIZABLE — Demostrar el Artefacto

```
Actúa como investigador aplicando la metodología Design Science Research (Johannesson & Perjons, 2014) para la actividad "Demonstrate Artefact" (Cap. 8 del libro).

ARTEFACTO DESARROLLADO (entregable del Paso 3, o descríbelo si aún no está formalizado):
[DESCRIPCION_DEL_ARTEFACTO_Y_COMPONENTES]

CONTEXTO ADICIONAL:
- Tipo de caso al que tengo acceso realista (ficticio diseñado por mí, caso documentado en literatura, caso real con datos propios, combinación): [TIPO_DE_CASO_DISPONIBLE]
- Datos/escenario concretos disponibles para ese caso: [DATOS_ESCENARIO]
- Qué aspecto del problema original quiero que la demostración ilustre con más fuerza: [ASPECTO_A_ILUSTRAR]

TAREA:

1) CHOOSE OR DESIGN CASE: Propón un caso concreto (ficticio, documentado o real, según lo que tengo disponible) para poner a prueba el artefacto. Justifica por qué este caso es representativo del problema explicitado y por qué es suficientemente desafiante (no trivial) para servir de "proof of concept" real.

2) APPLY ARTEFACT: Describe paso a paso cómo se aplicaría (o se aplicó) el artefacto a ese caso, y qué resultado se obtiene/obtuvo. Sé explícito sobre qué inputs entran, qué proceso interno sigue el artefacto, y qué outputs produce en este caso concreto.

FORMATO DE SALIDA:
- Descripción del caso elegido + justificación de su representatividad y nivel de exigencia
- Aplicación paso a paso del artefacto al caso (inputs → proceso → outputs)
- Resultado obtenido, interpretado en el contexto del problema original
- Declaración explícita de qué % o qué componentes del artefacto fueron efectivamente probados en esta demostración (y cuáles quedaron sin probar, para dejarlo claro de cara a la evaluación del Paso 5)
- Aclaración de que esta demostración es una forma "débil" de evaluación (proof of concept), no un reemplazo del Paso 5 "Evaluate Artefact"

Si no tengo datos suficientes para un caso real, ayúdame a diseñar un caso ficticio razonable, dejando explícito qué supuestos estás introduciendo.
```

## Marcadores a completar

- `[DESCRIPCION_DEL_ARTEFACTO_Y_COMPONENTES]`: pega el entregable del Paso 3 (artefacto + design rationale).
- `[TIPO_DE_CASO_DISPONIBLE]`: p. ej. "caso real: dataset de mediciones LiDAR capturado en laboratorio + simulación en Isaac Sim".
- `[DATOS_ESCENARIO]`: descripción concreta del entorno/datos (ej. distancias, condiciones de superficie, ángulos, ruido).
- `[ASPECTO_A_ILUSTRAR]`: p. ej. "que el modelo de regresión reproduce el patrón de ruido del sensor real en superficies reflectantes".
