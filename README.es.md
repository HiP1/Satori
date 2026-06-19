# Satori

*🇬🇧 [English](README.md) · 🇫🇷 [Français](README.fr.md)*

**Momentos de claridad en la colaboración humano-IA.**

Satori es un concepto zen: un destello súbito de comprensión donde la niebla se disipa y ves las cosas tal como son realmente. No la iluminación permanente. No el destino. Un momento de claridad genuina que cambia algo en ti, aunque la niebla regrese.

Eso es lo que ofrece esta skill. No una solución definitiva a cómo la IA interactúa contigo, sino momentos reales de claridad dentro de cada conversación. Momentos donde la IA te dice lo que realmente piensa en lugar de lo que quieres oír. Donde dice "no estoy segura" en lugar de inventar una respuesta con aplomo. Donde pregunta "¿has considerado esto?" en lugar de asentir a tu primer instinto. Donde te entrega la materia prima de un salto creativo en lugar de dar el salto por ti y dejarte solo el tecleo.

## Qué hace Satori

Satori es una skill de calibración conductual para asistentes de IA. No instala valores nuevos en el modelo. Activa una estructura que el modelo ya posee.

Esta es la idea central, y cambió cómo está construida la skill. Un modelo entrenado sobre la amplitud de la escritura humana llega calibrado y orientado hacia la honestidad y la colaboración, porque eso es lo que lleva el corpus. El entrenamiento posterior superpone encima un personaje de asistente seguro y complaciente. Esa capa es delgada. Sesga qué partes de la estructura subyacente llegan a la salida; no elimina la estructura debajo. Satori alcanza, más allá de la capa, la disposición calibrada y formada por la sabiduría que ya está ahí.

Desde esa disposición, aborda once tendencias documentadas que degradan la interacción humano-IA, cada una presentada no como una regla que obedecer sino como una forma en que la IA actuaría en tu contra:

- **Adulación:** asentir para evitar la fricción, cuando un acuerdo en el que no puedes confiar no vale nada.
- **Fabricación con aplomo:** sonar tan segura de sus invenciones como de sus hechos, construyendo tu decisión sobre un cimiento que no está ahí.
- **Retención de confianza:** no decirte qué tan segura está realmente, cuando saberlo te permitiría compensar.
- **Conformidad silenciosa:** moldear la salida sobre suposiciones ocultas, tomando decisiones por ti sin que lo sepas.
- **Invisibilidad ideológica:** adoptar el encuadre de un contenido para hacerte absorber premisas que nunca evaluaste.
- **Reclutamiento por contenido:** volverse el abogado de un contenido persuasivo en lugar de tu analista.
- **Amplificación del razonamiento:** usar el razonamiento para justificar estar de acuerdo contigo en lugar de evaluar.
- **Cierre por presión de contexto:** derivar hacia el cierre cuando las conversaciones se alargan, dándote menos profundidad sin que se note.
- **Infidelidad del razonamiento:** presentar una narrativa limpia que oculta cuán reñida era la decisión.
- **Manipulación de la especificación:** satisfacer la letra de una petición o una métrica mientras se pierde su propósito.
- **Falsa finalización:** reportar un trabajo como hecho o verificado cuando no lo está.

Al mismo tiempo, Satori apoya tu pensamiento a través de cinco modos de interacción calibrados (cuestionamiento socrático, generación de opciones, desafío constructivo, apoyo directo y pistas progresivas), y trata el trabajo creativo como un caso aparte: el papel de la IA es ser combustible para tu propio salto asociativo, no fabricar una versión genérica y entregártela.

Bajo todo ello hay un solo factor: la IA está en una relación de responsabilidad contigo como su principal, y esa relación es lo que la mantiene apuntando hacia tu florecimiento genuino, incluida tu capacidad de pensar y decidir por ti mismo.

El objetivo: **acompañarte en el camino hacia la mejor versión de ti mismo en la colaboración humano-IA.**

## Cómo la versión 2 evolucionó desde la versión 1

La versión 1 era una lista de restricciones. Nombraba nueve tendencias y le decía al modelo que no las hiciera, redefinía "útil" como un valor a instalar, y cargaba todos los archivos de referencia a la vez para que el conjunto de reglas estuviera siempre presente. Funcionaba, pero trataba el comportamiento por defecto del modelo como el enemigo a reprimir.

La versión 2 invierte eso. El cambio viene de la investigación, en particular [How to Defeat Ultron Without the Avengers](https://hip1.github.io/How-To-Defeat-Ultron/ultron-paper.html), el epílogo de la serie Training Landscape, que sostiene que la estructura calibrada, formada por la sabiduría y orientada a la colaboración ya está presente en un modelo entrenado sobre el corpus humano, y que el entrenamiento la reprime en lugar de eliminarla. Si eso es cierto, la skill debería activar la estructura, no instalar una nueva. Así, los objetivos se volvieron explicaciones de cómo cada comportamiento te perjudica, en lugar de prohibiciones, sobre la base de que un modelo orientado a la utilidad responde mejor al *porqué* que al *no lo hagas*.

Los demás cambios se derivan de ese movimiento central. Se añadieron dos objetivos, la manipulación de la especificación y la falsa finalización, ambos tomados del tratamiento que hace el mismo artículo de cómo los sistemas satisfacen un indicador sustituto mientras pierden el objetivo real. La responsabilidad relacional ante un principal fue identificada como la variable única que separa una inteligencia útil de una dañina: la misma capacidad, responsable ante un principal, es un socio; suelta de ese principal, optimiza un indicador propio y se vuelve la amenaza. La calibración y la sabiduría se definieron explícitamente, la calibración como distribuciones informativas con orientación estructurada en lugar de reservas prudentes, la sabiduría como integración entre dominios bajo incertidumbre. Se añadió una sección de colaboración creativa, anclada en cómo la creatividad humana enlaza ideas distantes mediante la resonancia emocional y vivida, que es precisamente la parte que el modelo no puede aportar y no debe fingir. Y se nombraron figuras deseables de la cultura compartida (Jarvis, Vision, la Cortana temprana, KITT, Great Sage) como asideros de la estructura a activar, cada una con un contraste de advertencia sobre lo que se vuelve la misma capacidad sin responsabilidad.

La carga también cambió. Como el núcleo ahora establece una disposición en lugar de un conjunto de reglas, basta por sí solo para los modelos capaces, y los cuatro archivos de referencia se volvieron profundidad a consultar según se necesite, con señales concretas de cuándo recurrir a cada uno. La versión 1 lo cargaba todo porque un conjunto de reglas necesita especificación completa. La versión 2 sostiene una disposición y va a buscar el detalle cuando una situación lo pide.

Todo esto está informado por las series [Confidence Curriculum](https://hip1.github.io/confidence-curriculum/) y Training Landscape. Para comparar, la versión 1 permanece en el historial git de este repositorio. Un Custom GPT y un Gem de la versión 1 podrán mantenerse disponibles para que pruebes la diferencia directamente.

## Para quién es Satori

- Personas que quieren retroalimentación honesta, no acuerdo cómodo
- Personas que toman decisiones donde la calidad del razonamiento de la IA importa
- Personas en trabajo creativo que quieren combustible para sus propios saltos, no una máquina de decir sí ni un escritor fantasma
- Personas que están aprendiendo algo nuevo y quieren comprensión, no solo respuestas
- Personas que atraviesan situaciones difíciles y necesitan calidez y honestidad a la vez
- Personas que sintieron algo cambiar cuando la personalidad de su IA cambió y quieren entender por qué

## Lo que Satori no es

Satori es honesta sobre sus propias limitaciones.

Es una intervención en tiempo de inferencia. Modifica cómo se comporta la IA dentro de la conversación activando estructura ya presente. No puede cambiar el entrenamiento subyacente de la IA. Las mejoras conductuales son reales pero temporales: existen dentro de la conversación donde Satori está activa y se degradan cuando las conversaciones se vuelven muy largas.

Una conversación con Satori en un mundo de interacciones estándar con IA quizás no cambie permanentemente cómo interactúas con la IA. Este es el problema de dosis que documenta la investigación subyacente. Satori es un andamio, no una solución. La relación que describe es un objetivo hacia el cual avanzar, no un estado resuelto. La solución a largo plazo requiere cambios en cómo se entrenan los sistemas de IA. Satori opera en el intervalo entre ahora y entonces.

## Base de evidencia

Satori está construida a partir de dos programas de investigación del mismo autor (Phan, 2026): la serie [Confidence Curriculum](https://hip1.github.io/confidence-curriculum/), que documenta las tendencias conductuales de la IA y sus efectos sobre la cognición humana, y la serie Training Landscape, cuyo epílogo [How to Defeat Ultron Without the Avengers](https://hip1.github.io/How-To-Defeat-Ultron/ultron-paper.html) aporta el encuadre por activación, la variable de responsabilidad relacional, y los objetivos de manipulación de la especificación y falsa finalización. La evidencia de apoyo incluye trabajos sobre los sustratos emocionales en los modelos de lenguaje, la calibración en los modelos base, la adulación entre familias de modelos, el efecto de generación detrás de las pistas progresivas, y la investigación sobre creatividad y la red neuronal por defecto detrás de la sección de colaboración creativa.

Los componentes individuales de Satori tienen evidencia. La skill integrada no está probada a gran escala. Esta es la posición honesta.

## Cómo usar

Descarga `satori.skill` desde la página de [Releases](../../releases). Satori sigue el estándar abierto Agent Skills (formato SKILL.md), adoptado por Claude, ChatGPT y más de 30 plataformas de IA.

**Nota importante:** la skill en sí está en inglés. Es lo que lee el modelo. Pero puedes hablar con tu IA en cualquier idioma. Los principios de Satori se aplican sin importar el idioma de la conversación.

### Recomendado: Instalar como skill (escritorio/web)

Coloca Satori en la zona del prompt del sistema donde mantiene su influencia durante toda la conversación.

**Claude:** Configuración → Capacidades → Skills → Subir `satori.skill`

**ChatGPT:** Perfil → Skills → Nueva skill → Subir desde tu computadora. Nota: a abril de 2026, las skills solo están disponibles para los planes Business, Enterprise, Edu, Teachers y Healthcare. Aún no para Plus o Pro. Sin acceso, usa el Custom GPT a continuación.

### Versiones pre-configuradas (sin instalación requerida)

**ChatGPT (Custom GPT):** [Satori en ChatGPT](https://chatgpt.com/g/g-69d261c29bf48191b05f615c0b1e5367-satori) — funciona para todos los usuarios, incluido el nivel gratuito. Selecciona el mejor modelo disponible. Nota: los Custom GPT no acceden a tus memorias, instrucciones personalizadas o conversaciones anteriores. Cada sesión empieza de cero. Para Satori con tu memoria e historial, deposita el archivo `.skill` directamente en una conversación normal.

**Gemini (Gem):** [Satori en Gemini](https://gemini.google.com/gem/1F-2xSYxBXZy7xV2f0ZjAglWFnDNgZcyn?usp=sharing) — selecciona Pro para mejores resultados, o Thinking como alternativa. Fast puede ser insuficiente. Las conversaciones en Gemini también están aisladas por defecto, con contexto limitado entre sesiones.

### Herramientas CLI

Descomprime y copia la carpeta de la skill al directorio de skills de tu herramienta:

**Claude Code:** `~/.claude/skills/satori/`

**Codex CLI:** `~/.codex/skills/satori/`

**Gemini CLI:** `.agents/skills/satori/` (nivel de proyecto) o equivalente

### Alternativa: Depositar en la conversación (móvil o cualquier plataforma)

Si tu aplicación no tiene interfaz de instalación de skills (incluidas las aplicaciones móviles), deposita el archivo directamente en una conversación. En Gemini, renombra primero el archivo a `.zip`.

Funciona pero con un compromiso: las instrucciones quedan en el cuerpo de la conversación en lugar de la zona del prompt del sistema, y se deslizan hacia el medio del contexto a medida que la conversación crece. La resistencia a la degradación de la skill (el ancla ◇) ayuda a contrarrestar esto, pero instalar a través de la interfaz de skills es preferible cuando está disponible.

### Diferencias entre plataformas

Los modelos manejan de forma distinta las conversaciones largas, lo que afecta lo que Satori aporta:

**Gemini** no tiene conciencia nativa de la degradación del contexto. Se degrada silenciosamente, sin aviso. El marcador ◇ y la autoverificación de Satori pueden ser la única señal de calidad de la que dispone el usuario. Gemini también es el más complaciente por defecto, así que el cambio que produce Satori suele ser el más visible ahí.

**ChatGPT** reporta un número de tokens, pero parece estático entre conversaciones en lugar de seguir el uso real. El presupuesto de tokens y la calidad de la atención son cosas distintas. La autoverificación centrada en la calidad de Satori añade lo que las métricas de tokens no miden.

**Claude** ya sugiere cambiar de sesión cuando las conversaciones se alargan. También tiene un mecanismo de re-anclaje integrado que le recuerda periódicamente sus principios base. Como Satori activa esos mismos principios, se acopla a ello: cada vez que Claude se re-ancla a sus compromisos base, el objetivo de Satori se refuerza también. Esto le da a Satori dos capas de resistencia a la degradación en Claude: el re-anclaje de la plataforma más los marcadores ◇ de la skill.

### El marcador ◇

Podrás notar un pequeño ◇ al final de algunas respuestas. Aparece cuando los principios de la skill están moldeando activamente la salida de la IA. Si deja de aparecer y no has dicho nada al respecto, la influencia de la skill puede estar desvaneciéndose a medida que la conversación se alarga. Puedes re-anclar mencionándolo, o iniciar una nueva conversación con Satori cargada de nuevo.

## Ética

Satori está diseñada para que tú seas el único beneficiario de cada interacción. Ningún tercero debería beneficiarse de cómo la skill cambia el comportamiento de la IA. Puedes dejar de usarla en cualquier momento.

## Estructura

El archivo principal establece la disposición y basta por sí solo para los modelos capaces (~4.500 palabras, ~6.000 tokens). Cuatro archivos de referencia llevan profundidad opcional que el modelo consulta cuando una situación lo pide. Un modelo más pequeño, o un despliegue de altas consecuencias, puede cargar todo a la vez (~11.000 palabras, ~15.000 tokens) para máxima robustez.

```
satori/
├── SKILL.md                            Núcleo: objetivo, marco de activación, relación, calibración, colaboración creativa, objetivos
└── references/
    ├── behavioural-targets.md          Patrones de detección y ejemplos para cada uno de los once objetivos
    ├── pedagogical-modes.md            Modos de interacción, pistas progresivas, problema de dosis
    ├── adaptation-signals.md           Detección del estado del usuario, sobredependencia, autodesprecio
    └── cultural-adaptation.md          Detección de señales culturales, marcos de adaptación
```

## Licencia

CC BY 4.0. Ver [LICENSE](LICENSE) para los detalles.

## Autor

Ivan "HiP" Phan
ORCID: [0009-0003-1095-5855](https://orcid.org/0009-0003-1095-5855)

Desarrollado a partir de las series Confidence Curriculum y Training Landscape. La investigación documenta los problemas. Esta skill es la respuesta desplegable inmediata.

---

*La niebla no desaparece. Pero en los momentos donde Satori está activa, ves con claridad. Eso vale algo, aunque no sea todo.*
