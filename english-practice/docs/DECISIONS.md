# DECISIONS — Programa de producción oral en inglés

Bitácora del porqué. Append-only. Se consulta por búsqueda; no se lee entera.

## Índice

- 2026-08-23 — Se rotan tres actividades y se estudia día de por medio
- 2026-08-23 — Sprint de recuperación como ejercicio de vocabulario
- 2026-08-23 — La calificación la da la IA de cada persona, no el agente ni un par
- 2026-08-23 — La página expone método y ruta, no solo la lección del día
- 2026-08-23 — Tarea escrita los viernes, sobre el mismo tema ya hablado
- 2026-08-23 — El mes tiene rampa de dificultad y checkpoints en los días 1 y 20
- 2026-08-23 — El agente es de texto: el habla sale del canal y se reporta
- 2026-08-23 — La lección vive en una página que el agente edita, no en el chat
- 2026-08-23 — Se añaden gramática y diccionario, con un límite explícito de tamaño
- 2026-08-23 — Ejecución en grupo de WhatsApp con bot orquestador, no herramienta individual
- 2026-08-23 — La corrección vive fuera del grupo, en el chat privado de cada miembro
- 2026-08-23 — El bot no registra calidad, solo participación
- 2026-08-20 — Bloque de repetición dos veces por semana, no diario
- 2026-08-20 — Banco semilla de 120 chunks con caducidad deliberada el día 12
- 2026-08-20 — Espaciado de repaso corto y expansivo (+2/+6/+15)
- 2026-08-20 — Material sesgado a formas fijas, no a plantillas con hueco
- 2026-08-19 — La métrica objetivo son las pausas a mitad de frase
- 2026-08-19 — Repetición del mismo contenido con tiempo constante; se descarta el 4/3/2
- 2026-08-19 — Feedback en modo prompt, nunca recast
- 2026-08-19 — Shadowing, lectura en voz alta y entrenamiento de pronunciación descartados
- 2026-08-19 — Sin tutor de pago

---

### 2026-08-23 — Se rotan tres actividades y se estudia día de por medio

- **Por qué:** el programa era una sola actividad repetida veinte veces. Eso protege la
  dosis pero maltrata la adherencia, que es la restricción que de verdad manda aquí. Y
  el objetivo del usuario se amplió: no solo hablar, también vocabulario y escritura.
  La rotación es compatible con la evidencia siempre que **hablar siga siendo el eje**,
  y lo sigue siendo: cuatro sesiones de habla al mes son veinte narraciones, y la dosis
  que produjo transferencia medida en el ensayo aleatorizado fue de doce.
- **Cada actividad tiene un papel declarado, no es relleno.** Hablar es el motor.
  Vocabulario alimenta lo que se puede decir, y sobre todo entrena la *velocidad* de
  recuperación, que explica diez veces más varianza en pausas que el hecho de conocer
  la palabra. El ensayo es *noticing*: escribir con tiempo muestra qué frases sabes
  construir y no te salen hablando.
- **El seguro contra la dilución:** toda sesión termina hablando dos minutos, sea del
  tipo que sea. Sin eso, una semana entera podría pasar sin producir habla.
- **Día de por medio (lunes, miércoles, viernes)** en vez de a diario. Doce sesiones al
  mes. Los estudios que funcionaron usaron dosis pequeñas; los que fallaron usaron
  treinta y dos horas de pronunciación o dieciséis semanas de shadowing. Fijar la
  actividad a un día de la semana elimina además la decisión diaria.
- **Alternativas descartadas:**
  - *Mantener habla todos los días:* protege la dosis y pierde el grupo.
  - *Rotar dentro de cada sesión (un poco de todo cada día):* fragmenta el bloque de
    repetición, que necesita las cinco rondas seguidas el mismo día.
  - *Cuatro o cinco actividades:* cada una recibiría dos sesiones al mes, demasiado
    poco para que ninguna cuaje.
- **Reemplaza a:** 2026-08-23, "El mes tiene rampa de dificultad", en cuanto al número
  de sesiones y su distribución. La rampa por tipo de tarea sigue vigente.

### 2026-08-23 — Sprint de recuperación como ejercicio de vocabulario

- **Por qué:** una sesión de vocabulario que solo presenta expresiones nuevas construye
  conocimiento declarativo, y saber una expresión explica el 0,8% de la varianza en
  pausas. Lo que explica el 10,7% es la velocidad para recuperarla. El sprint entrena
  exactamente eso: dieciocho frases ya vistas, sesenta segundos, decirlas en voz alta y
  pasar. Da un número que debería subir a lo largo del mes.
- **Se alimenta de material ya visto**, nunca del nuevo: es una prueba de acceso, no de
  aprendizaje. Y sirve de repaso espaciado adicional.
- **Alternativas descartadas:**
  - *Más tarjetas nuevas:* construye la parte que no predice fluidez.
  - *Quiz escrito con puntaje:* mide reconocimiento, que es lo contrario de lo que hace
    falta. El sprint se hace en voz alta a propósito.

### 2026-08-23 — La calificación la da la IA de cada persona, no el agente ni un par

- **Por qué:** faltaba una señal de progreso dentro del día. El agente no puede darla
  (modelo básico, y evaluar mal hace daño) y los pares tampoco (poco fiables, y el
  error de un par se propaga). La IA propia de cada miembro sí puede, escuchando en
  segundo plano mientras se habla, y no cuesta fricción adicional porque la persona ya
  tiene una abierta.
- **Lo que se calificó es la decisión, no que se califique.** El prompt puntúa **una
  sola cosa**: si se traba a mitad de frase. Prohíbe explícitamente comentar acento,
  pronunciación, muletillas, repeticiones y autocorrecciones, y ordena calificar contra
  el propio nivel y no contra un nativo. Una nota global de "qué tan bueno es tu
  inglés" habría sido desmoralizante y habría medido otra cosa.
- **La nota no se compara entre personas** ni sale en el resumen semanal: sirve para
  ver la tendencia de cada quien contra sí mismo.
- **Alternativas descartadas:**
  - *Que el agente califique:* no puede sostener el criterio y opinar sobre una nota lo
    convierte en juez, que es justo lo que el diseño le prohíbe ser.
  - *Calificación entre pares:* propaga errores y activa la espiral de cortesía.
  - *Métricas automáticas dentro de la página:* requeriría audio, que el canal no tiene.

### 2026-08-23 — La página expone método y ruta, no solo la lección del día

- **Por qué:** el programa se leía como veinte días sueltos. Sin ver el porqué ni el
  arco, la gente no distingue entre "hoy no me dio tiempo" y "esto no lleva a nada", y
  lo segundo es lo que hace abandonar. La pestaña **Método** resume el diagnóstico en
  tres minutos, con el gráfico de pausas por nivel; **La ruta** muestra los veinte días
  con su foco y su trampa, y explica por qué ese orden y no otro.
- **Detalle:** la primera visita abre en Método, no en Hoy. Después ya no.
- **Alternativas descartadas:**
  - *Dejar el porqué solo en los documentos:* nadie abre un PDF adjunto a diario.
  - *Un onboarding modal:* se cierra sin leer y no se puede volver a consultar.

### 2026-08-23 — Tarea escrita los viernes, sobre el mismo tema ya hablado

- **Por qué:** escribir no entrena hablar —la destreza es específica y esa es la tesis
  del programa entero— así que la tarea escrita no se justifica como práctica de
  fluidez. Se justifica como **noticing**: escribir sobre el mismo tema, minutos
  después de haberlo hablado y con tiempo para pensar, hace visible la diferencia entre
  lo que la persona sabe construir y lo que le sale en tiempo real. Esa diferencia es,
  literalmente, la brecha que el programa ataca.
- **El orden importa:** siempre después de hablar, nunca antes. Escribir primero
  convertiría el bloque en recitación de un guion.
- **Uno por semana, no más.** Cuatro en el mes. Si crece, compite con el bloque.
- **Alternativas descartadas:**
  - *Ensayo sobre un tema distinto:* pierde la comparación, que es todo el valor.
  - *Escritura diaria:* desplaza tiempo del único ejercicio que sí transfiere.

### 2026-08-23 — El mes tiene rampa de dificultad y checkpoints en los días 1 y 20

- **Por qué:** el plan anterior era plano — el día 20 exigía exactamente lo mismo que
  el día 1 — y no tenía medición dentro del mes, así que no podía demostrar nada. La
  rampa va por **tipo de tarea**, que es la dimensión con base empírica: narrativo →
  descriptivo → explicativo → argumentativo. El narrativo es el más barato porque el
  orden cronológico funciona como andamiaje; el argumentativo es el más caro porque
  exige postura más concesión. El tiempo sube solo entre semanas (90 s → 2 min) y
  **nunca dentro de un día**, que es lo que la regla de tiempo constante exige.
- **Checkpoints en los días 1 y 20:** la misma consigna grabada sin preparar. Sin eso
  el mes produce una sensación, no un resultado. Es también lo que hace que el día 20
  cierre en vez de simplemente acabarse.
- **Puente al mes 2:** el día 20 el agente devuelve a cada persona su lista completa de
  huecos del mes, íntegra. El mes 2 se arma de ahí y no de otra lista general — que es
  el punto entero de haberlos recogido.
- **Se restituye la llamada del sábado**, que se había caído al reescribir el sistema
  para solo texto. No requiere que el agente maneje audio: solo publica el aviso. Es la
  única media hora síncrona de la semana, y 4,5 h repartidas en 12 semanas fue la dosis
  que produjo d = 1,14 en el estudio de referencia.
- **Alternativas descartadas:**
  - *Subir el número de rondas con las semanas:* las rondas 4 y 5 son las que producen
    el efecto; recortarlas al principio quitaría justo lo que funciona.
  - *Rampa por abstracción del tema en vez de por tipo de tarea:* más difusa de
    ejecutar y sin la misma base empírica.
  - *Checkpoint semanal:* medir cada semana es ruido — los cambios detectables tardan
    semanas, y medir de más garantiza el abandono.

### 2026-08-23 — El agente es de texto: el habla sale del canal y se reporta

- **Por qué:** el agente disponible no maneja audio. Como el ejercicio central es
  producir habla, la alternativa era degradar el programa a ejercicios escritos —
  que es exactamente lo que la evidencia dice que no transfiere. La resolución es
  sacar el habla del canal: el bloque se hace en voz alta por fuera y se reporta por
  texto. La adherencia no se sostiene con verificación sino con que alguien pregunte
  todos los días, así que perder la verificación cuesta poco.
- **Alternativas descartadas:**
  - *Convertir el bloque en un ejercicio escrito:* habría rehecho el error de fondo.
    La destreza es específica; escribir no entrena hablar.
  - *Pedir que suban los audios a otro sitio y peguen el enlace:* añade tres pasos de
    fricción al único ejercicio obligatorio. La fricción es la variable que mata esto.
  - *Cambiar de plataforma para conservar el audio:* el grupo ya está en WhatsApp.
- **Reemplaza a:** 2026-08-23, "Ejecución en grupo de WhatsApp con bot orquestador",
  en lo relativo al manejo de audio. El resto de esa entrada sigue vigente.

### 2026-08-23 — La lección vive en una página que el agente edita, no en el chat

- **Por qué:** un mensaje de chat se pierde hacia arriba en el hilo; una página se
  hojea y se repasa. Y como las lecciones anteriores no se borran, el repaso espaciado
  del vocabulario funciona de verdad: el reto de cada día son frases de los días −2,
  −6 y −15, que solo existen si el archivo las conserva.
- **Detalle de diseño:** la página tiene un único bloque editable delimitado, que
  contiene solo datos. El agente pega objetos ya redactados; no compone HTML. El
  render va envuelto en try/catch y muestra un aviso accionable si el bloque queda mal
  pegado, en vez de quedarse en blanco.
- **Alternativas descartadas:**
  - *Que el agente reescriba la página entera cada día:* un modelo básico rompería
    estilos y estructura.
  - *Reemplazar la lección en vez de acumularlas:* mataría el repaso espaciado.
  - *Un archivo JSON aparte que la página cargue:* más limpio, pero depende de cómo
    se aloje la página y añade un modo de fallo silencioso.

### 2026-08-23 — Se añaden gramática y diccionario, con un límite explícito de tamaño

- **Por qué:** se pidió que la página fuera más didáctica y no solo de habla. Es
  compatible con la evidencia siempre que cada pieza tenga su rol declarado: la
  instrucción explícita funciona, pero el conocimiento gramatical nace declarativo y
  solo se vuelve utilizable al hablar si se produce. Por eso cada punto de gramática
  trae tres frases para decir en voz alta, y hay **uno solo por día**.
- **El límite es la decisión, no la adición.** Si la gramática crece, se come el
  tiempo del bloque de habla y el programa se convierte en comprensión, que tiene
  efecto ~0 sobre producción. El bloque queda marcado en la página como lo único
  obligatorio.
- **Sobre el reto escrito:** entrena formulación (recuperar la palabra y armar la
  frase), que es el cuello de botella real — la articulación no lo es. Pero por
  especificidad de destreza no transfiere entero al habla, así que complementa el
  bloque y nunca lo reemplaza. Queda dicho así en la página y en las instrucciones.
- **Alternativas descartadas:**
  - *Un temario de gramática progresivo:* convierte el programa en un curso.
  - *Diccionario de palabras sueltas:* las secuencias fijas de varias palabras son lo
    que reduce pausas; dentro de una expresión automatizada no se puede pausar.

### 2026-08-23 — Ejecución en grupo de WhatsApp con bot orquestador, no herramienta individual

- **Por qué:** el protocolo se sostiene sobre producir habla, y la nota de voz de
  WhatsApp es el medio de producción con menos fricción disponible en un teléfono.
  Además el grupo restaura el diseño original de la repetición de tarea, que es
  repetir la misma charla **a oyentes distintos** — la versión en solitario perdía
  esa mitad, y con ella la tasa de articulación se degradaba por aburrimiento
  (g = −0,88 a −1,73 en el estudio de repetición masiva). Y el grupo aporta gratis
  el interlocutor humano que se había descartado pagar: 4,5 h totales en 12 semanas
  bastaron para d = 1,14 en ratio de pausas, con solo 5–15% de los errores corregidos.
- **Alternativas descartadas:**
  - *Seguir con la herramienta HTML individual:* funciona, pero deja la adherencia
    enteramente a la voluntad del usuario. La restricción real de este programa nunca
    fue la dosis (12 narraciones bastaron en el ensayo aleatorizado) sino el abandono.
  - *Telegram u otra plataforma con mejor soporte de bots:* no se evaluó a fondo. El
    grupo ya existe en WhatsApp y mover la plataforma añade una fricción que compite
    con la única variable que importa, que es que la gente aparezca.
- **Reemplaza a:** 2026-08-20, en cuanto al canal de ejecución. El protocolo, el
  banco de material y el calendario de espaciado siguen vigentes sin cambios.

### 2026-08-23 — La corrección vive fuera del grupo, en el chat privado de cada miembro

- **Por qué:** el bot disponible es un modelo básico. La forma de feedback que
  funciona —señalar el error y hacer reintentar— rinde d = 0,83; darle al alumno la
  versión correcta rinde 0,53. Un modelo básico tiende por defecto a lo segundo, y
  además no puede juzgar de forma fiable si el reintento quedó bien. Delegarle la
  corrección compraría la mitad del efecto y con ruido. Separar la máquina de
  eventos de recuperación (que no necesita juicio y sí puede hacer el bot) de la
  máquina de corrección de errores (que sí lo necesita) deja a cada pieza haciendo
  lo que puede hacer bien.
- **Alternativas descartadas:**
  - *El bot corrige con límites estrictos:* aun acotado, un modelo básico no puede
    sostener el modo prompt a lo largo de un intercambio.
  - *Corrección entre pares dentro del grupo:* se conserva parcialmente, en forma de
    respuesta cruzada obligatoria después de cada bloque, pero no como corrección
    gramatical — los pares no son fiables en eso y el error de un par se propaga.
  - *David hace de puente pasando los audios a un modelo fuerte:* máxima calidad,
    pero lo convierte en cuello de botella diario y el programa muere cuando él se
    ocupa.

### 2026-08-23 — El bot no registra calidad, solo participación

- **Por qué:** un registro de calidad mal hecho da al grupo una señal falsa y
  convierte la participación en algo que se puede perder. La métrica que se publica
  es colectiva (minutos de habla producidos por el grupo) porque es exactamente la
  variable que el protocolo quiere maximizar.
- **Alternativas descartadas:**
  - *Ranking o "mejor de la semana":* mide otra cosa y expulsa al último, que suele
    ser quien más lo necesita. En un grupo de cuatro, perder a uno es perder el 25%
    de los oyentes distintos de los que depende el ejercicio.
  - *Que el bot calcule palabras por minuto transcribiendo:* la transcripción
    automática de habla acentuada tiene una tasa de error varias veces peor que la
    de referencia, y la métrica se prestaría a comparaciones entre personas.

### 2026-08-20 — Bloque de repetición dos veces por semana, no diario

- **Por qué:** dos bloques semanales son 10 narraciones, y el ensayo aleatorizado que
  midió mejoras en pausas a mitad de frase sobre prompts nuevos, sostenidas a 28
  días, usó 12 narraciones **en total**. En la segunda semana ya se supera la dosis
  efectiva. Ponerlo los cinco días no compraría más efecto y costaría la adherencia.
- **Alternativas descartadas:**
  - *Bloque diario:* 25 min diarios de repetición en grupo agota la atención del
    hilo y satura de audios. Las intervenciones que fallaron en la literatura son
    justamente las de mucho volumen (32 h de pronunciación, 16 semanas de shadowing).
  - *Un solo bloque semanal:* llega a la dosis, pero deja seis días sin producción
    estructurada y el hábito no se sostiene.
- **Nota:** los días concretos (martes y jueves) son arbitrarios. El único ensayo que
  comparó intervalos de 1 día contra 7 días entre sesiones no encontró diferencia.
  Lo que no se mueve es que las 5 rondas de un bloque ocurran el mismo día.

### 2026-08-20 — Banco semilla de 120 chunks con caducidad deliberada el día 12

- **Por qué:** el drill se alimenta de los huecos propios del hablante, pero el día 1
  no existe ninguno. El banco resuelve el arranque y se agota a propósito: para el
  día 13 hay 12 sesiones de cosecha acumuladas, y ese material es estrictamente mejor
  porque sale de fallos reales de recuperación en vez de una lista general.
- **Alternativas descartadas:**
  - *Banco permanente de varios cientos de chunks:* convierte el programa en estudio
    de vocabulario, que es reconocimiento y no producción.
  - *Empezar directamente con material propio:* imposible el día 1, y arrancar sin
    material es la forma más común de no arrancar.

### 2026-08-20 — Espaciado de repaso corto y expansivo (+2/+6/+15)

- **Por qué:** va al revés de la intuición de Anki. Para vocabulario declarativo,
  espaciar más rinde más; para destreza **procedimental** oral la evidencia se
  invierte (Suzuki 2017 encontró 3 días mejor que 7; Li & DeKeyser confirmaron que lo
  procedimental prefiere intervalos cortos y lo declarativo largos). El repaso a +15
  existe solo para atrapar la caída documentada a las dos semanas.
- **Alternativas descartadas:**
  - *Espaciado estándar tipo SRS (1/3/7/21/60):* optimizado para reconocimiento, que
    no es lo que se entrena aquí.

### 2026-08-20 — Material sesgado a formas fijas, no a plantillas con hueco

- **Por qué:** un estudio de 2025 sobre 120 narraciones hablada encontró que solo la
  proporción de secuencias **fijas** se relaciona positivamente con la fluidez de
  velocidad; las de hueco abierto a veces no promueven ni velocidad ni reducción de
  pausas, y reutilizadas o corregidas pueden empeorar la fluidez de reparación.
- **Alternativas descartadas:**
  - *Patrones productivos tipo "I'm ___ing to ___":* más generativos en teoría, pero
    exigen codificación gramatical en el momento, que es justo el cuello de botella.

### 2026-08-19 — La métrica objetivo son las pausas a mitad de frase

- **Por qué:** comparando B2 → C1 → nativo en la misma tarea, las pausas en el límite
  de frase apenas se mueven (5,80 → 5,96 → 4,64 por 100 palabras) porque los nativos
  también planifican ahí. Las pausas **dentro** de la frase caen a un tercio (6,42 →
  3,78 → 2,06). Además la velocidad de habla hace techo en B2 y deja de desarrollarse.
- **Alternativas descartadas:**
  - *Velocidad de habla como objetivo:* techo en B2; el entrenamiento por repetición
    consistentemente no mueve la tasa de articulación.
  - *Duración media de pausa:* 61% determinada por el estilo al hablar en L1.
    Perseguirla es perseguir la propia personalidad.
  - *Muletillas y auto-correcciones:* r ≈ −0,15 a −0,20 con fluidez percibida; los
    nativos hacen ~6,3 muletillas/min; no se movieron en 5 meses de inmersión.
  - *Acento y pronunciación:* 32 h de entrenamiento dieron efecto nulo sobre
    inteligibilidad y fluidez en habla espontánea.

### 2026-08-19 — Repetición del mismo contenido con tiempo constante; se descarta el 4/3/2

- **Por qué:** es la única técnica con transferencia demostrada a temas nuevos y
  sostenida a 4 semanas. El grupo de control que hizo los mismos tiempos con temas
  distintos ganó cero, lo que aísla la repetición como ingrediente activo. Sobre el
  reloj: comparado de frente, el tiempo constante (3/3/3) rindió igual o mejor que el
  4/3/2 en fluidez, precisión, léxico, sintaxis y contenido; la presión temporal
  degrada la precisión y empuja a recitar de memoria.
- **Alternativas descartadas:**
  - *4/3/2 clásico con reloj decreciente:* ver arriba. Además, el test más directo
    sobre presión temporal encontró que limita tanto el procesamiento controlado como
    el automático, contra la predicción teórica.
  - *Repetición masiva (6 rondas seguidas):* reduce pausas pero enlentece la
    articulación y aumenta la repetición literal; a la semana todo converge.
  - *Tres rondas en vez de cinco:* las pausas de mitad de frase siguen mejorando
    hasta la ronda 4; parar en 3 es quedarse justo antes del objetivo.

### 2026-08-19 — Feedback en modo prompt, nunca recast

- **Por qué:** prompts (señalar y hacer reintentar) d = 0,83; corrección explícita
  0,84; recasts (dar la versión correcta) 0,53. El efecto es máximo sobre habla libre
  (d = 0,97) y el feedback inmediato se sostiene a dos semanas mientras el diferido
  no. Los prompts generan un evento de recuperación; los recasts no.
- **Alternativas descartadas:**
  - *Dejar que la IA reformule y seguir la conversación:* es el comportamiento por
    defecto de toda app de conversación con IA, y es el modo con la mitad del efecto.

### 2026-08-19 — Shadowing, lectura en voz alta y entrenamiento de pronunciación descartados

- **Por qué:** shadowing — 22 sesiones en 16 semanas dieron nulo en velocidad y en
  reparación; lo único que se movió fue la ubicación de las pausas, y el 83% de los
  participantes creía que estaba funcionando. Lectura en voz alta — 11 semanas sin
  aumento de velocidad de habla. Pronunciación — 32 h sin efecto sobre habla
  espontánea. Los tres se recomiendan mucho y ninguno cruza a la producción libre.
- **Alternativas descartadas:** conservarlos como complemento de bajo coste. Se
  descartó porque compiten por el mismo tiempo que el único ejercicio que sí
  transfiere, y porque generan sensación de progreso sin progreso.

### 2026-08-19 — Sin tutor de pago

- **Por qué:** preferencia explícita del usuario, no falta de evidencia. La capa de
  interlocutor humano se cubre con opciones gratuitas (y desde 2026-08-23, con el
  propio grupo). La dosis necesaria es baja: 4,5 h totales en 12 semanas produjeron
  d = 1,14 en ratio de pausas, con feedback sobre solo el 5–15% de los errores.
- **Alternativas descartadas:** tutor semanal en italki o similar. Es la variable que
  más aceleraría el resultado; queda anotada por si la preferencia cambia.
