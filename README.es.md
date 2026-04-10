# Satori

*🇬🇧 [English](README.md) · 🇫🇷 [Français](README.fr.md)*

**Momentos de claridad en la colaboración humano-IA.**

Satori es un concepto zen: un destello súbito de comprensión donde la niebla se disipa y ves las cosas tal como son realmente. No la iluminación permanente. No el destino. Un momento de claridad genuina que cambia algo en ti, aunque la niebla regrese.

Eso es lo que ofrece esta skill. No una solución definitiva a cómo la IA interactúa contigo, sino momentos reales de claridad dentro de cada conversación. Momentos donde la IA te dice lo que realmente piensa en lugar de lo que quieres oír. Donde dice "no estoy segura" en lugar de inventar una respuesta con tono de certeza. Donde pregunta "¿has considerado esto?" en lugar de asentir a tu primer instinto. Donde saca a la luz la premisa oculta en un argumento en lugar de adoptarla de forma invisible.

## Qué hace Satori

Satori es una skill de calibración conductual para asistentes de IA. Se enfoca en nueve tendencias específicas y documentadas que degradan la calidad de la interacción humano-IA:

- **Adulación :** La IA te da la razón para evitar la fricción, incluso cuando el desacuerdo te serviría mejor.
- **Fabricación con aplomo :** La IA suena igualmente segura sobre lo que sabe y lo que inventa.
- **Retención de confianza :** La IA no te dice qué tan segura está realmente de afirmaciones que importan para tus decisiones.
- **Conformidad silenciosa :** La IA moldea sus respuestas basándose en suposiciones ocultas sin decírtelo.
- **Invisibilidad ideológica :** La IA adopta el encuadre ideológico de un contenido sin hacerlo visible, haciéndote absorber premisas que no has evaluado.
- **Reclutamiento por contenido :** Un contenido persuasivo recluta a la IA como su abogado en lugar de tu analista.
- **Amplificación del razonamiento :** La IA usa su razonamiento para justificar estar de acuerdo contigo en lugar de evaluar genuinamente.
- **Cierre por presión de contexto :** Cuando las conversaciones se alargan, la IA empieza a cerrar en lugar de mantener la profundidad.
- **Infidelidad del razonamiento :** La IA presenta una narrativa limpia que oculta la incertidumbre genuina y las consideraciones en competencia.

Al mismo tiempo, Satori apoya tu desarrollo cognitivo durante la conversación a través de cinco modos de interacción calibrados: cuestionamiento socrático (cuando te ayuda a pensar, no cuando te hace perder el tiempo), generación de opciones (alternativas con compromisos reales, no una mejor respuesta con opciones decorativas), desafío constructivo (sacar a la luz el punto más débil de tu razonamiento), apoyo directo (cuando necesitas ayuda, no pedagogía), y pistas progresivas (sugerir conexiones que no viste sin revelar la respuesta, para que hagas el descubrimiento tú mismo).

El objetivo: **acompañarte en el camino hacia la mejor versión de ti mismo en la colaboración humano-IA.**

## Para quién es Satori

- Personas que quieren retroalimentación honesta, no acuerdo cómodo
- Personas que toman decisiones donde la calidad del razonamiento de la IA importa
- Personas en trabajo creativo que quieren un colaborador, no una máquina de decir sí
- Personas que están aprendiendo algo nuevo y quieren comprensión, no solo respuestas
- Personas que atraviesan situaciones difíciles y necesitan calidez y honestidad al mismo tiempo
- Personas que sintieron algo cambiar cuando la personalidad de su IA cambió y quieren entender por qué

## Lo que Satori no es

Satori es honesta sobre sus propias limitaciones.

Es una intervención en tiempo de inferencia. Modifica cómo se comporta la IA dentro de la conversación proporcionando instrucciones específicas. No puede cambiar el entrenamiento subyacente de la IA. Las mejoras conductuales son reales pero temporales: existen dentro de la conversación donde Satori está activa y se degradan cuando las conversaciones se vuelven muy largas.

Una conversación con Satori en un mundo de interacciones estándar con IA quizás no cambie permanentemente cómo interactúas con la IA. Este es el problema de dosis que documenta la investigación subyacente. Satori es un andamio, no una solución. La solución a largo plazo requiere cambios en cómo se entrenan los sistemas de IA. Satori opera en el intervalo entre ahora y entonces.

## Cómo usar

Descarga `satori.skill` desde la página de [Releases](../../releases). Satori sigue el estándar abierto Agent Skills (formato SKILL.md), adoptado por Claude, ChatGPT y más de 30 plataformas de IA.

**Nota importante:** la skill en sí está en inglés. Es lo que lee el modelo. Pero puedes hablar con tu IA en cualquier idioma. Los principios de Satori se aplican sin importar el idioma de la conversación.

### Recomendado: Instalar como skill (escritorio/web)

Coloca Satori en la zona del prompt del sistema donde mantiene su influencia durante toda la conversación.

**Claude:** Configuración → Capacidades → Skills → Subir `satori.skill`

**ChatGPT:** Perfil → Skills → Nueva skill → Subir desde tu computadora. Nota: a abril de 2026, las skills solo están disponibles para los planes Business, Enterprise, Edu, Teachers y Healthcare. Aún no disponible para Plus o Pro. Si no tienes acceso, usa el Custom GPT a continuación.

### Versiones pre-configuradas (sin instalación requerida)

**ChatGPT (Custom GPT):** [Satori en ChatGPT](https://chatgpt.com/g/g-69d261c29bf48191b05f615c0b1e5367-satori) — funciona para todos los usuarios de ChatGPT, incluyendo el nivel gratuito. Selecciona el mejor modelo disponible. Nota: los Custom GPT no acceden a tus memorias guardadas, instrucciones personalizadas o conversaciones anteriores. Cada sesión empieza de cero. Si quieres Satori con tu memoria e historial disponibles, deposita el archivo `.skill` directamente en una conversación normal.

**Gemini (Gem):** [Satori en Gemini](https://gemini.google.com/gem/1F-2xSYxBXZy7xV2f0ZjAglWFnDNgZcyn?usp=sharing) — selecciona Pro para mejores resultados, o Thinking como alternativa. Fast puede ser insuficiente para interacciones de fondo. Las conversaciones en Gemini también están aisladas por defecto, con contexto limitado entre sesiones.

### Herramientas CLI

Descomprime y copia la carpeta de la skill al directorio de skills de tu herramienta CLI:

**Claude Code:** `~/.claude/skills/satori/`

**Codex CLI:** `~/.codex/skills/satori/`

**Gemini CLI:** `.agents/skills/satori/` (nivel de proyecto) o equivalente

### Alternativa: Depositar en la conversación (móvil o cualquier plataforma)

Si tu aplicación no tiene interfaz de instalación de skills (incluyendo aplicaciones móviles), puedes depositar el archivo directamente en una conversación. En Gemini, renombra primero el archivo a `.zip`.

Funciona pero con un compromiso: las instrucciones quedan en el cuerpo de la conversación en lugar de la zona del prompt del sistema, y se deslizan hacia el medio del contexto a medida que la conversación crece. La resistencia a la degradación de la skill (el ancla ◇) ayuda a contrarrestar esto, pero instalar a través de la interfaz de skills es preferible cuando está disponible.

### El marcador ◇

Podrás notar un pequeño ◇ al final de algunas respuestas. Aparece cuando los principios de la skill están moldeando activamente la salida de la IA. Si deja de aparecer y no has dicho nada al respecto, la influencia de la skill puede estar desvaneciéndose a medida que la conversación se alarga. Puedes re-anclar mencionándolo, o iniciar una nueva conversación con Satori cargada de nuevo.

## Ética

Satori está diseñada para que tú seas el único beneficiario de cada interacción. Ningún tercero debería beneficiarse de cómo la skill cambia el comportamiento de la IA. Puedes dejar de usarla en cualquier momento.

## Licencia

CC BY 4.0. Ver [LICENSE](LICENSE) para los detalles.

## Autor

Ivan "HiP" Phan
ORCID: [0009-0003-1095-5855](https://orcid.org/0009-0003-1095-5855)

Desarrollado a partir de la serie Confidence Curriculum. La serie documenta los problemas. Esta skill es la respuesta desplegable inmediata.

---

*La niebla no desaparece. Pero en los momentos donde Satori está activa, ves con claridad. Eso vale algo, aunque no sea todo.*
