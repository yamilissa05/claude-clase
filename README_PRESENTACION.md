# Positioning Lab — Find your place

> *“Un buen producto puede perderse en un mal posicionamiento.”*

Simulador educativo interactivo · Negocios Digitales · Semana 5

---

## Cómo abrirlo

1. Abre la carpeta del proyecto.
2. Haz doble clic en **`index.html`**. No necesita internet, servidor, instalación ni build.
3. Para sacar capturas rápidas, abre `index.html?evidence=true` (aparece un panel lateral; la tecla **E** lo muestra u oculta).

| Archivo | Qué es |
|---|---|
| `index.html` | La experiencia completa (HTML + CSS + JS vanilla en un único archivo). |
| `README_PRESENTACION.md` | Este documento: fundamentos, decisiones y guion. |
| `evidencias/*.png` | 16 capturas listas (desktop y móvil). |
| `evidencias/Evidencias_Positioning_Lab.pdf` | Borrador del PDF de evidencias (portada con campos en blanco para completar). |

---

## 1. Tema seleccionado

**Posicionamiento.**

## 2. Objetivo de la experiencia

Que cualquier persona, sepa o no qué es posicionamiento, aprenda **decidiendo**: para quién posicionar un producto, qué necesidad atacar, cómo leer a la competencia, qué es el sweet spot, cómo interpretar un mapa perceptual y cómo construir un positioning statement. Todo en 5–7 minutos, dentro de una historia y sin leer teoría antes de actuar.

## 3. Cómo funciona

El usuario es el consultor que debe rescatar el lanzamiento de **NOVA**, una app ficticia para universitarios que el equipo quiere vender como *“una app de productividad para todos”*. Faltan 20 minutos para el lanzamiento.

| # | Misión | Tipo de interacción | Concepto que se aprende |
|---|---|---|---|
| 0 | Briefing | Aceptar la misión | Qué problema tiene NOVA (producto bueno, posicionamiento inexistente) |
| 1 | ¿Para quién? | **Selección simple** + visualización alcance/relevancia | Target customer · estrategia demográfica |
| 2 | Encuentra la necesidad | **Selección múltiple** de insights de entrevistas | Customer needs (C1) · necesidad vs. deseo vs. característica |
| 3 | Sweet spot | **Combinación** de una tarjeta por cada C en un diagrama de Venn | 3C: Customer needs + Company competencies + Competitor gaps |
| 4 | Perception map | **Arrastrar** NOVA en un mapa perceptual (también clic o flechas del teclado) | Clusters, zonas saturadas, gaps, diferenciación |
| 5 | Positioning statement | **Constructor** pieza por pieza (For / Who / Is a / That / Unlike / We) | Elevator pitch format y sus criterios de calidad |
| 6 | Test del mercado | **Evaluación de piezas** publicitarias + estrategia de touchpoints | Posicionamiento ≠ slogan · consistencia entre canales |
| 7 | Resultado | **Dashboard dinámico** | Score calculado a partir de las decisiones reales |
| — | Cierre y Customer Journey | Visualización del aprendizaje y del recorrido | Síntesis del tema y del journey de la propia experiencia |

**Cómo se calcula el puntaje (no es aleatorio):** cada opción tiene un valor según su calidad estratégica. Si el usuario se equivoca y corrige, el primer intento y la corrección pesan 50/50: puede equivocarse sin quedar bloqueado, pero el error se refleja.

| Métrica | Fórmula |
|---|---|
| Target clarity | Misión 1 (60%) + pieza “FOR” del statement (40%) |
| Customer fit | Misión 2 (50%) + “WHO” (25%) + necesidad elegida en las 3C (25%) |
| Differentiation | Sweet spot (35%) + mapa perceptual (35%) + categoría/beneficio/alternativa/ventaja del statement (30%) |
| Message consistency | Anuncio elegido (50%) + estrategia de touchpoints (50%) |
| **Positioning score** | Promedio de las cuatro |

Con decisiones ideales se obtiene 100/100 (**LAUNCH READY**); con decisiones débiles, alrededor de 36/100 (**LAUNCH AT RISK**). El dashboard señala la métrica más débil y ofrece volver a esa misión.

## 4. Conceptos académicos utilizados

Fuentes: *Developing a Product Positioning* (Digital Product Management, cap. 12) y *Online Retail and Services* (E-commerce, cap. 9).

- **Posicionamiento.** Cómo percibe el cliente un producto frente a sus competidores y qué lugar ocupa en su mente. Responde para quién es, qué problema resuelve, cómo lo resuelve y por qué elegirlo frente a las alternativas. En el juego, NOVA empieza con un posicionamiento inexistente y el jugador lo construye.
- **Customer perception map.** Representación visual de cómo los clientes perciben productos según dos atributos relevantes. Se lee identificando **clusters** (productos percibidos como intercambiables), **gaps** (espacios con necesidad no cubierta) y **outliers**. En el juego los ejes son *Complejo ↔ Simple* y *Generalista ↔ Universitario*, y el mapa aclara que muestra **percepciones**, no especificaciones técnicas.
- **Sweet spot (3C).** El posicionamiento competitivo fuerte aparece donde coinciden **Customer needs** (lo que el cliente valora), **Company competencies** (lo que la empresa sabe hacer de verdad y es difícil de copiar) y **Competitor gaps** (lo que la competencia no resuelve bien). En NOVA: *“todo claro sin configurar cinco apps” + “unifica tareas, horarios y equipos automáticamente” + “las alternativas son fragmentadas o complejas” = Productividad universitaria sin fricción.*
- **Estrategias de posicionamiento** (precio, calidad, demografía, categoría, diferenciación, competencia). No se presentan como definiciones: aparecen dentro de las decisiones. Por ejemplo, el target por edad (demografía), la categoría “workspace académico” frente a “calendario” (categoría), “a diferencia de las herramientas generalistas” (competencia) y la opción de comunicar solo descuentos (precio).
- **Positioning statement.** Formato de elevator pitch: *For* (target) · *Who* (necesidad) · *Our product* · *Is a* (categoría) · *That* (beneficio) · *Unlike* (alternativa) · *Our product* (ventaja competitiva). Debe ser claro, específico, breve, diferenciado y centrado en el cliente. El juego lo evalúa con cinco indicadores: TARGET, NEED, CATEGORY, VALUE y DIFFERENTIATION.
- **Consistencia de touchpoints.** El núcleo del posicionamiento se mantiene en todos los canales y la ejecución se adapta a cada medio (casual en redes, explicativo en la landing, directo en la App Store). Conecta con la experiencia omnicanal integrada y *frictionless* del capítulo de Online Retail.

## 5. Decisiones de UX

- **Progressive disclosure.** La teoría aparece solo cuando se necesita: el concepto se revela en la tarjeta de feedback *después* de la decisión (“Concepto · Sweet spot · 3C”). Las zonas del mapa (cluster, gap) se muestran recién al fijar la posición y los checks de los anuncios, al elegir uno.
- **Feedback inmediato.** Cada interacción sigue el patrón *acción → consecuencia → aprendizaje*: una tarjeta con el veredicto, qué pasaría en el mercado y el microaprendizaje. Además, el dossier lateral actualiza las métricas en vivo con flechas ↑/↓ (en pantallas chicas aparece como aviso flotante).
- **Learning by doing.** Primero se elige y después se explica. Nunca se muestran definiciones antes de decidir.
- **Visibility of system status.** El HUD fijo muestra `MISSION n/6`, una barra de progreso segmentada, la cuenta regresiva y **la etapa del Customer Journey en la que está el usuario** (cambia a “Retroalimentación” cuando aparece un feedback). El dossier muestra las decisiones tomadas y las 3C encendidas.
- **Error-friendly design.** Ninguna respuesta bloquea: siempre se puede continuar, reconsiderar o volver. Los errores se explican sin tono de examen (“Target demasiado amplio”, no “Incorrecto”). El reinicio pide confirmación para evitar pérdidas accidentales.
- **Jerarquía visual.** Una pregunta central por pantalla, títulos grandes, una sola acción primaria (color acento) y acciones secundarias neutras. Los correctos e incorrectos no dependen solo del color: siempre llevan símbolo (✓ ◐ !) y texto.
- **Accesibilidad.** Botones semánticos, `role="radio"`/`aria-checked` en elecciones únicas, foco visible, foco al título en cada cambio de misión, mapa manejable con flechas, anuncios para lectores de pantalla, contraste alto y soporte de `prefers-reduced-motion`.

## 6. Customer Journey de mi entregable

La propia experiencia está diseñada como un journey. El botón **“Ver mi Customer Journey”** muestra el recorrido real del usuario (su tiempo y sus decisiones en cada etapa) con objetivo, touchpoint, interacción, emoción esperada y una curva emocional.

| Etapa | Dónde ocurre | Objetivo del usuario | Touchpoint | Interacción | Emoción esperada |
|---|---|---|---|---|---|
| **1. Entrada** | Portada | Entender la misión en segundos | Portada con cuenta regresiva y ficha de NOVA | Pulsar “Aceptar misión” | Curiosidad + urgencia |
| **2. Exploración** | Misiones 1–2 | Descubrir el problema y el mercado | Segmentos, mapa de audiencia, entrevistas | Comparar segmentos, separar necesidades de ruido | Intriga |
| **3. Interacción** | Misiones 3–5 | Tomar decisiones estratégicas | Diagrama 3C, mapa perceptual, constructor | Combinar, arrastrar, construir | Control, sentirse estratega |
| **4. Retroalimentación** | Transversal + misión 6 | Entender las consecuencias | Tarjetas de feedback, dossier en vivo, test de mercado | Leer, corregir, validar | “Ajá”, aprender del error |
| **5. Resultado** | Dashboard | Ver el impacto total | Score, métricas, antes/después, decision log | Revisar y volver a la misión más débil | Logro (o reto) |
| **6. Cierre** | Debrief + journey | Consolidar lo aprendido | Cadena Customer → Touchpoints | Repasar, reiniciar | Claridad y confianza |

## 7. Decisiones visuales

- **Dark mode premium** (`#0A0A0A`), texto blanco hueso (`#EDE8DF`) y **un solo acento eléctrico** (lima `#D4FF3F`) reservado para lo importante: acción principal, éxito y sweet spot. Un naranja cálido funciona como señal de alerta, siempre acompañado de símbolo y texto.
- **Tipografía sans moderna para contenido y monoespaciada para datos** (labels, métricas, log). Así se ve como una herramienta estratégica y no como una presentación.
- **Grid de fondo sutil, cards sobrias, bordes de 1 px y sombras mínimas**: la jerarquía viene del espacio y del tamaño, no de efectos.
- **Microanimaciones con propósito**: aparición del feedback, barras que se llenan, puntos del mapa, pulso del sweet spot, conteo del score. Se desactivan con `prefers-reduced-motion`.
- **Identidad propia**: NOVA tiene su símbolo (una órbita con un punto acento) para que las piezas publicitarias parezcan reales. No copia ninguna marca.
- **Sin dependencias externas**: fuentes del sistema, sin CDN. Funciona offline.

## 8. Guion oral (3–5 min, referencia)

> **[Apertura, 30 s]**
> “¿Alguna vez vieron un producto bueno que nadie entendía para qué servía? Ese es el problema que quise convertir en experiencia. Mi tema es posicionamiento, y en vez de explicarlo con diapositivas hice un simulador: *Positioning Lab*.”
>
> **[El caso, 30 s]** *(mostrar portada)*
> “El jugador es consultor de NOVA, una app para universitarios. El producto funciona y el mercado existe, pero el equipo quiere venderla como ‘una app de productividad para todos’. Quedan 20 minutos para el lanzamiento y la misión es que el cliente entienda tres cosas: para quién es, qué problema resuelve y por qué NOVA.”
>
> **[Target y necesidades, 45 s]** *(misiones 1 y 2)*
> “Primero hay que elegir a quién le hablamos. Si elijo ‘todos’, el juego no me dice ‘incorrecto’: me muestra la consecuencia. Tengo mucho alcance, pero la relevancia se cae. Cuando elijo universitarios que combinan clases, tareas y proyectos, el mercado se achica pero el mensaje se vuelve relevante. Después escucho entrevistas y separo necesidades reales, como centralización, claridad, coordinación y menos fricción, de cosas como ‘quiero estudiar 12 horas’, que es un deseo y no un problema.”
>
> **[Sweet spot y mapa, 60 s]** *(misiones 3 y 4, la parte más visual)*
> “Aquí está el corazón del tema: las 3C de la lectura. Cruzo lo que el cliente necesita, lo que NOVA sabe hacer y lo que la competencia no resuelve. Si elijo una competencia que NOVA no tiene, como una IA que escribe trabajos, no hay intersección: sería prometer algo que no puedo cumplir. Cuando las tres coinciden aparece el sweet spot: ‘productividad universitaria sin fricción’.
> Luego lo llevo al mapa perceptual. NOVA hoy está en medio del cluster de apps generalistas, que es una zona saturada. La arrastro hacia ‘simple + universitario’ y el sistema detecta el gap. Algo importante: el mapa muestra percepciones de los estudiantes, no características técnicas.”
>
> **[Statement y mercado, 45 s]** *(misiones 5 y 6)*
> “Con eso armo el positioning statement pieza por pieza: For, Who, Is a, That, Unlike, We. Cada opción vaga, como ‘es mejor’ o ‘usa tecnología’, recibe feedback. Después viene la prueba del mercado: ¿qué anuncio refleja el posicionamiento? Y en los canales, la respuesta correcta es mantener el mismo posicionamiento y adaptar la ejecución a cada medio. Así se ve que el posicionamiento no es un slogan.”
>
> **[Resultado y journey, 45 s]** *(dashboard y journey)*
> “Al final hay un score que sale de las decisiones reales. Si juego mal da 36; si juego bien, 100. Y como la actividad pedía Customer Journey, la propia experiencia lo implementa: Entrada, Exploración, Interacción, Retroalimentación, Resultado y Cierre. Durante todo el juego el HUD muestra en qué etapa está el usuario, y al final se ve su journey con tiempos y decisiones.”
>
> **[Cierre, 15 s]**
> “La idea que quiero dejar: el posicionamiento no es lo que la empresa dice que es, sino el lugar que logra ocupar en la mente del cliente frente a sus alternativas.”

## 9. Preguntas que podría hacer el profesor

1. **¿Cuál es la diferencia entre posicionamiento y propuesta de valor?**
   La propuesta de valor describe el valor que el producto entrega al cliente. El posicionamiento es el lugar que ese valor ocupa en la mente del cliente **en comparación con las alternativas**. La propuesta de valor es un insumo; el posicionamiento agrega el contexto competitivo (el *Unlike*).

2. **¿Por qué el mapa perceptual representa percepción y no necesariamente realidad?**
   Porque se construye con opiniones de clientes (encuestas, reseñas, focus groups). TASKLY puede tener buenas funciones y aun así percibirse como “complejo”. Para el posicionamiento importa lo que el cliente cree, porque decide con base en eso.

3. **¿Qué sucede si hay una necesidad, pero la empresa no tiene la competencia para resolverla?**
   No hay sweet spot. Posicionarse ahí sería una promesa que no se puede cumplir y el cliente lo nota. Es la trampa de la tarjeta “IA que redacta trabajos”. O la empresa desarrolla esa competencia, o busca otra intersección.

4. **¿Qué representa el sweet spot?**
   La intersección de necesidad del cliente, competencia real de la empresa y gap de la competencia. Es una posición relevante (el cliente la quiere), creíble (la empresa puede cumplirla) y diferenciada (nadie más la ocupa).

5. **¿Por qué elegiste esos dos ejes del mapa?**
   Porque salen de las necesidades detectadas: los estudiantes piden simplicidad (“no quiero otra app complicada”) y soluciones pensadas para su vida académica. La lectura dice que los ejes deben ser atributos importantes para el cliente y que diferencien a los productos. Precio y calidad no separaban bien a estos competidores.

6. **¿Cuál fue el Customer Journey de tu propia experiencia?**
   Entrada (portada y misión) → Exploración (target y necesidades) → Interacción (3C, mapa y statement) → Retroalimentación (feedback en cada decisión y test del mercado) → Resultado (dashboard) → Cierre (lo aprendido y el journey). Cada etapa tiene objetivo, touchpoint, interacción y emoción esperada.

7. **¿Dónde aplicaste UX?**
   En el feedback inmediato (acción → consecuencia → aprendizaje), el progressive disclosure, el HUD con el estado del sistema, el diseño error-friendly (nada bloquea), una decisión por pantalla, la accesibilidad por teclado, el diseño responsive y el respeto a reduced motion.

8. **¿Cómo sabes que el posicionamiento es diferente al slogan?**
   El statement es interno y estratégico: guía todo. El slogan es una ejecución creativa para comunicarlo. “Tu universidad. En orden.” es un slogan que **expresa** el posicionamiento; la misión 6 lo demuestra porque se elige el anuncio que refleja el statement.

9. **¿Por qué el mensaje debe conservar consistencia entre canales?**
   Porque el posicionamiento se construye por repetición coherente en cada touchpoint. Si cada canal dice algo distinto, el cliente recibe tres marcas y ninguna posición se fija. La lectura lo resume así: el núcleo se mantiene y el mensaje se adapta al medio.

10. **¿Cuál es el aprendizaje principal del juego?**
    Que el mejor posicionamiento aparece cuando una necesidad relevante del cliente coincide con una capacidad real de la empresa y un espacio que los competidores no satisfacen, y que después hay que comunicarlo de forma consistente.

11. **¿Qué estrategias de posicionamiento aparecen en el juego?**
    Demografía (target por perfil universitario), categoría (workspace académico vs. calendario), diferenciación (simple + integrado), competencia (“a diferencia de las herramientas generalistas”) y precio (la opción de usar solo descuentos, que se muestra como un error para NOVA). Calidad aparece implícita en la promesa de experiencia simple.

12. **¿Por qué un target más pequeño es mejor si el mercado se achica?**
    Porque aumenta la relevancia. Un mensaje específico hace que el segmento se reconozca de inmediato. Hablarle a todos produce un mensaje genérico que no convence a nadie.

13. **¿El score no es arbitrario?**
    Cada opción tiene un valor según su calidad estratégica y las fórmulas son públicas (sección 3). El mismo motor da 100 con decisiones ideales y 36 con decisiones débiles. Corregir recupera la mitad del puntaje.

14. **¿Cualquier espacio vacío en el mapa es una oportunidad?**
    No. Un hueco sin demanda es una trampa. En el juego, si NOVA se ubica en “complejo + generalista” o en el centro, el feedback lo explica: el gap tiene que coincidir con una necesidad real.

15. **¿Por qué la categoría “calendario” recibe puntaje bajo si NOVA tiene calendario?**
    Porque define contra quién te comparan. Como calendario, NOVA compite en la categoría de CALENDAR+, que ya tiene líder. Como “workspace académico” crea un marco propio donde su ventaja se entiende.

16. **¿Cómo medirías si el posicionamiento funcionó en la vida real?**
    Con las métricas del capítulo: percepción y awareness (encuestas), ventas y market share, satisfacción y NPS, benchmarking competitivo, sentimiento en reseñas y focus groups. Si el mercado cambia, se vuelve a hacer el mapa.

17. **¿Qué relación tiene esto con el capítulo de Online Retail?**
    Ese capítulo habla de core competencies difíciles de copiar (la C2), de experiencias integradas y *frictionless* entre canales (la consistencia de touchpoints) y de disruptores como Lemonade, que ganan simplificando un proceso complejo. Es la misma lógica que usa NOVA frente a competidores complejos.

18. **¿Por qué no hiciste un quiz?**
    Porque en un quiz se memoriza. Aquí cada pantalla usa un tipo de interacción distinto (selección simple, múltiple, combinación, drag en el mapa, constructor de frases, evaluación de anuncios) y cada decisión tiene una consecuencia visible dentro de una historia.

---

## Anexo técnico

- **Stack:** HTML + CSS + JavaScript vanilla en un solo archivo. Sin frameworks, sin build, sin CDN, sin backend.
- **Arquitectura:** contenido en objetos de datos (`TARGETS`, `INSIGHTS`, `THREE_C`, `MAP_POINTS`, `SLOTS`, `ADS`, `CHANNELS`, `JOURNEY`), un único objeto `state` con todas las decisiones, funciones de scoring puras (`metrics()`), vistas por fase con `html()` (estructura) y `sync()` (estado → UI), y un solo listener delegado para todas las acciones (`data-action`).
- **Estilos:** variables CSS (tokens), componentes reutilizables (`.opt`, `.fb`, `.tok`, `.btn`, `.panel`), responsive con tres breakpoints y `prefers-reduced-motion`.
- **Evidence mode:** `?evidence=true` abre el panel de estados. `?shot=<fase>` salta directo a un estado (`intro`, `target`, `needs`, `sweet`, `map`, `statement`, `market`, `channel`, `result`, `closing`, `journey`). `&mixed=1` usa decisiones débiles y `&clean=1` oculta el panel para la captura. Los estados se generan con el mismo motor del juego y no afectan la experiencia normal.
- **QA realizado:** recorrido completo automatizado en desktop (1440 px), tablet (834 px) y móvil (390 px) sin errores de consola ni overflow horizontal; navegación completa por teclado; recálculo del score al cambiar decisiones; HTML renderizado validado con html-validate.
