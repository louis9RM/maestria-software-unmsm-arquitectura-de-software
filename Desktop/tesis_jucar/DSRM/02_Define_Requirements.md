# PASO 2 — Define Requirements (Definir Requisitos)

> Fuente: Johannesson & Perjons (2014), *An Introduction to Design Science*, **Capítulo 6** (pp. 103-116).
> Segunda actividad del Method Framework for Design Science Research (Sect. 4.1).

---

## 1. Qué exige el libro en este paso

**Pregunta que debe responder esta actividad (textual del libro, Cap. 6):**
> "What artefact can be a solution for the explicated problem and which requirements on this artefact are important for the stakeholders?"
> ("¿Qué artefacto puede ser una solución para el problema explicitado, y qué requisitos sobre ese artefacto son importantes para los stakeholders?")

Esta actividad se entiende como una **continuación/profundización de la explicitación del problema**: los investigadores siguen explorando el problema, pero ahora usando el esbozo de solución propuesto como "lente" de análisis. El resultado es conocimiento *descriptivo* que especifica requisitos.

**Definición de "requisito" (Cap. 6):** una propiedad de un artefacto considerada deseable por los stakeholders de una práctica, que debe guiar el diseño y desarrollo del artefacto.

---

## 2. Sub-actividades obligatorias (Sect. 6.1)

1. **Outline Artefact (Esbozar el artefacto, 6.1.1):** decidir **qué tipo de artefacto** se va a diseñar, entre las 4 categorías establecidas del libro (Cap. 2.3.1):
   - **Construct** (constructo): términos, notaciones, definiciones, conceptos necesarios para formular el problema/solución.
   - **Model** (modelo): representación de una posible solución (ej. un modelo de regresión, una arquitectura).
   - **Method** (método): guías/procesos para resolver problemas o lograr metas.
   - **Instantiation** (instanciación): un sistema funcionando que puede usarse en una práctica (ej. un software, un prototipo).
   Luego describir el artefacto elegido a nivel de visión general (overview).

2. **Elicit Requirements (Elicitar requisitos, 6.1.2):** identificar los requisitos concretos, que pueden clasificarse en:
   - **Requisitos funcionales**: qué funciones debe ofrecer el artefacto (dependen del problema y de las necesidades de los stakeholders).
   - **Requisitos no funcionales**, que a su vez se dividen en:
     - **Requisitos estructurales**: sobre la estructura del artefacto (ver "Structural Qualities" abajo).
     - **Requisitos ambientales/de entorno**: sobre la relación del artefacto con su entorno (ver "Environmental Qualities" abajo).
   - Opcionalmente, **metas/requisitos sobre efectos** del uso del artefacto (ej. "debe aumentar la precisión en un X%").

   El libro recomienda trazar cada requisito hacia una **causa raíz** identificada en el Paso 1 (si el problema fue analizado con causas raíz, cada requisito debería poder rastrearse a una o varias de ellas).

   **Requisitos en conflicto:** el libro reconoce que distintos stakeholders pueden proponer requisitos que no pueden cumplirse simultáneamente. Recomienda pedir a los stakeholders que **prioricen/rankeen** los requisitos sugeridos para resolver estos conflictos.

---

## 3. Insumos (input) para este paso

- El **problema explicitado** (Paso 1), idealmente con sus causas raíz.

## 4. Entregable (output) de este paso

Un **esbozo del artefacto** (tipo + descripción general) y una **lista de requisitos** (funcionales, estructurales, ambientales), cada uno justificado y, si es posible, trazado a una causa raíz del problema. Este entregable alimenta directamente el Paso 3 (Design and Develop Artefact).

## 5. Recursos que el libro indica usar (Sect. 6.2)

- Literatura previa sobre soluciones similares al problema (incluso si no existe una solución idéntica, hay que indicar qué tan parecidas son las que sí existen y en qué difieren).
- Intereses y opiniones de los stakeholders.

## 6. Estrategias y métodos de investigación sugeridos para ESTE paso (Sect. 6.3)

| Estrategia/método | Ventaja para elicitar requisitos | Riesgo/desventaja |
|---|---|---|
| Encuestas | Bajo costo, llega a muchos stakeholders y grupos distintos | Requisitos incompletos si los respondientes no dedican tiempo/esfuerzo |
| Estudios de caso | Permite identificar requisitos incluso si el stakeholder no los declara explícitamente | Consume mucho tiempo; limita generalización (un solo caso local) |
| Investigación-acción | Útil cuando el artefacto es muy novedoso y los stakeholders no comprenden aún su potencial | Riesgo de que el investigador imponga su propia visión |
| Entrevistas | Método más común; permite preguntas de seguimiento | Puede volverse rígida si es muy estructurada; depende del esfuerzo del respondiente |
| Grupos focales | Mayor creatividad al combinar personas con backgrounds distintos | Riesgo de dominancia de algunos participantes (mitigable con buen moderador) |
| Cuestionarios | Mismo perfil que entrevistas, pero aún más barato | Poca creatividad; útil sobre todo para *rankear* requisitos ya identificados |
| Observación | Genera requisitos que el investigador infiere, útil si los stakeholders no comprenden bien el artefacto propuesto | Depende mucho de la competencia del investigador |
| Documentos | Complementa otros métodos o sustituye cuando hay acceso limitado a stakeholders | Igual limitación que en el paso anterior |

## 7. Guías explícitas del libro para este paso (Sect. 6.4)

- Especificar qué artefacto se va a construir (tipo + características generales).
- Formular cada requisito de forma clara, precisa y concisa.
- Justificar cada requisito (por qué es necesario, relacionándolo con el problema).
- Ser realista, pero también intentar ser original.
- Especificar las fuentes de los requisitos (literatura y stakeholders).
- Describir cómo se definieron los requisitos (cómo se involucró a los stakeholders, cómo se revisó la literatura).

## 8. Cualidades genéricas para inspirar/validar requisitos no funcionales (Sect. 6.5)

**Cualidades estructurales:** Coherencia, Consistencia (solo modelos), Modularidad (bajo acoplamiento, alta cohesión, alta recomponibilidad), Concisión.

**Cualidades ambientales — de uso:** Usabilidad, Comprensibilidad, Aprendibilidad, Personalizabilidad, Idoneidad/precisión, Accesibilidad, Elegancia, Diversión, Trazabilidad (solo métodos).

**Cualidades ambientales — de gestión:** Mantenibilidad, Flexibilidad, Responsabilización (*accountability*).

**Cualidades ambientales genéricas:** Expresividad (constructos/modelos), Corrección (modelos), Generalidad, Interoperabilidad (instanciaciones), Autonomía (instanciaciones), Proximidad (modelos), Completitud, Efectividad, Eficiencia, Robustez (instanciaciones), Resiliencia (instanciaciones).

**Marco de las 5Es (Sect. 6.6, Checkland & Scholes 1999)** — lista corta alternativa de cualidades de alto nivel: **Eficacia** (efectos deseables en condiciones ideales), **Eficiencia** (sin desperdiciar tiempo/esfuerzo/costo), **Efectividad** (efectos deseables en la práctica real), **Elegancia** (agradable/estéticamente satisfactorio), **Eticidad** (adherencia a normas éticas).

## 9. Criterio de salida — cuándo pasar al Paso 3

Cuando tengas (a) el tipo de artefacto decidido, (b) una lista de requisitos funcionales y no funcionales justificados, y (c) al menos un intento de priorización si hay requisitos en conflicto.

---

## 🔧 PROMPT REUTILIZABLE — Definir Requisitos

```
Actúa como investigador aplicando la metodología Design Science Research (Johannesson & Perjons, 2014) para la actividad "Define Requirements" (Cap. 6 del libro).

PROBLEMA EXPLICITADO (entregable del Paso 1, o descríbelo si aún no lo tienes formalizado):
[PROBLEMA_EXPLICITADO_CON_CAUSAS_RAIZ]

CONTEXTO ADICIONAL:
- Idea preliminar de solución (si ya tengo una intuición de qué construir): [IDEA_PRELIMINAR_DE_ARTEFACTO]
- Stakeholders cuyas opiniones puedo recoger para requisitos: [STAKEHOLDERS]
- Soluciones existentes similares que conozco (aunque no resuelvan exactamente el mismo problema): [SOLUCIONES_EXISTENTES]
- Restricciones de mi proyecto (tiempo, recursos, tecnología disponible): [RESTRICCIONES]

TAREA — Ejecuta las 2 sub-actividades de "Define Requirements":

1) OUTLINE ARTEFACT: Con base en el problema y sus causas raíz, decide y justifica qué TIPO de artefacto es el más adecuado entre las 4 categorías del libro: constructo, modelo, método o instanciación. Da una descripción general (overview) del artefacto propuesto (qué es, cómo se relaciona con la práctica descrita en el problema).

2) ELICIT REQUIREMENTS: Genera una lista de requisitos organizada en:
   a. Requisitos FUNCIONALES (qué debe hacer el artefacto) — cada uno trazado explícitamente a la causa raíz del problema que atiende.
   b. Requisitos ESTRUCTURALES (usa como inspiración: coherencia, consistencia, modularidad, concisión).
   c. Requisitos AMBIENTALES/de entorno (usa como inspiración: usabilidad, comprensibilidad, aprendibilidad, personalizabilidad, idoneidad, accesibilidad, mantenibilidad, flexibilidad, interoperabilidad, generalidad, efectividad, eficiencia, robustez, resiliencia — elige solo las relevantes para mi tipo de artefacto, no fuerces todas).
   d. Si detectas requisitos que entran en conflicto entre sí (no se pueden cumplir simultáneamente), señálalos explícitamente y sugiere un criterio de priorización.

FORMATO DE SALIDA — entrega:
- Tipo de artefacto elegido + justificación
- Descripción general del artefacto (overview)
- Tabla de requisitos: [ID | Requisito | Tipo (funcional/estructural/ambiental) | Causa raíz que atiende | Justificación]
- Conflictos detectados entre requisitos (si los hay) y criterio de priorización sugerido
- Fuentes usadas para derivar los requisitos (literatura / soluciones existentes / supuestos propios que deberías validar con stakeholders reales)

Si no tengo suficiente información sobre stakeholders o soluciones existentes para justificar algún requisito con rigor, indícamelo explícitamente en vez de asumir datos que no te di.
```

## Marcadores a completar

- `[PROBLEMA_EXPLICITADO_CON_CAUSAS_RAIZ]`: pega aquí el entregable completo del Paso 1.
- `[IDEA_PRELIMINAR_DE_ARTEFACTO]`: si ya tienes una intuición (ej. "un modelo de regresión estadística que emule el comportamiento del sensor LiDAR"), descríbela; si no, escribe "ninguna aún, ábrelo tú".
- `[STAKEHOLDERS]`: igual que en el Paso 1, o refinado.
- `[SOLUCIONES_EXISTENTES]`: papers, productos o proyectos similares que ya conozcas.
- `[RESTRICCIONES]`: p. ej. "tesis de pregrado, 6 meses, sin acceso a hardware adicional, usando NVIDIA Isaac Sim y datos públicos del datasheet del sensor".
