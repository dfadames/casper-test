# STATE — Programa de producción oral en inglés

**Contexto:** grupo de 3–5 hispanohablantes (Bogotá, UTC−5) con inglés receptivo
fuerte y producción oral débil. Se ejecuta en un grupo de WhatsApp con un agente de
**solo texto** que cada mañana actualiza una página con la lección del día, avisa al
grupo, lanza un reto de texto al mediodía y en la noche recoge quién hizo qué.

**Objetivo actual:** reducir las pausas a mitad de frase (formulación) en habla
espontánea, desde el rango B2 (~6,4 por 100 palabras) hacia C1 (~3,8).

## Decisiones vigentes

- El cuello de botella es la velocidad para recuperar una palabra, no el conocimiento.
- Métrica objetivo: pausas **dentro** de la frase. No velocidad (techo en B2), no
  acento, no muletillas.
- **Día de por medio: lunes, miércoles y viernes. Doce sesiones al mes.** La dosis
  efectiva es pequeña (12 narraciones en los estudios; aquí se hacen 20) y los
  programas de mucho volumen son los que fallaron.
- **Se rotan tres actividades**, una por día de la semana:
  lunes habla · miércoles vocabulario · viernes ensayo.
- Toda sesión termina hablando dos minutos, sea del tipo que sea.
- Habla: repetición del **mismo contenido**, 5 rondas, tiempo constante dentro del día,
  las 5 el mismo día. Sube entre semanas: 90 s en la S1, 2 min desde la S2.
- Vocabulario: 10 expresiones nuevas + **sprint de recuperación** (18 frases ya vistas
  en 60 s). El sprint mide velocidad de acceso, que es la variable que predice pausas.
- Ensayo: escribir contrarreloj y con diccionario cerrado, y después hablar el mismo
  tema. Es *noticing*, no entrenamiento de fluidez.
- **El habla ocurre fuera del canal.** El agente no maneja audio: asigna y registra.
- **Califica la IA de cada persona**, con prompts que trae la página: nota 1–10 sobre
  trabarse a mitad de frase, más dos correcciones. Prohíben comentar acento,
  pronunciación y muletillas. Entran solas en el reporte. El agente no opina.
- La página genera el reporte del día completo, listo para copiar.
- Tres pestañas: Método (por qué), La ruta (las 12 sesiones y su orden) y Hoy.
- La lección vive en `leccion.html`, con un bloque editable que contiene solo datos.
  Las sesiones viejas **no se borran**: la ruta, el repaso y el sprint las usan.
- Una sola trampa de gramática por sesión, con 3 frases para producir.
- Repaso espaciado a −1, −3 y −6 sesiones, vía el reto diario.
- Medición mensual con Praat + SyllableNuclei v3, umbral fijo en 0,25 s. Tarea fija:
  "Tell me about your last week, in order, including one thing that went wrong and
  what you did about it."
- Solo tema claro. Minimalista.

## Descartado

Razones completas en `DECISIONS.md`. Aquí solo lo que un lector frío repropondría:

- **Convertir el bloque en ejercicio escrito** porque el agente no maneja audio —
  sería rehacer el error de fondo: escribir no entrena hablar.
- **Un temario de gramática progresivo** — convierte el programa en un curso de
  comprensión, que tiene efecto ~0 sobre producción.
- **Diccionario de palabras sueltas** — lo que reduce pausas son las secuencias fijas.
- **Shadowing, lectura en voz alta, entrenamiento de pronunciación** — nulos sobre
  habla espontánea pese a ser lo más recomendado.
- **Acortar el reloj entre rondas (4/3/2)** — tiempo constante rinde igual o mejor.
- **Más input como entrenamiento** — efecto sobre producción ≈ 0. Es mantenimiento.
- **Que el agente corrija** — un modelo básico tiende al recast, que rinde la mitad.
- **Rankings** — expulsan al último, que es quien más lo necesita.

## Entregable

Todo va empaquetado en `practica-ingles/` (y su `.zip`). `README.md` es el punto de
entrada: basta con darle esa carpeta al agente. Verificado de punta a punta —
los 20 objetos del plan pegan limpio en la página y las 20 lecciones cargan sin error.

## Archivos impactados

Rutas relativas a la raíz del paquete `practica-ingles/`.

- `README.md` — punto de entrada. Qué es, cómo empezar, las seis reglas duras.
- `AGENTE.md` — instrucciones operativas del agente. Se pegan tal cual.
- `PLAN-MES-1.md` — 20 lecciones listas para pegar, más los tres mensajes de cada día.
- `leccion.html` — la app diaria: cronómetro de rondas, tarjetas de vocabulario, reto
  con autocorrección, generador del reporte y mapa del mes. Guarda el progreso
  localmente. Bloque editable delimitado; falla con aviso legible, no en blanco.
- `recursos/chunks-anki.tsv` · `recursos/sesion-individual.html` — tarjetas de
  producción y la versión en solitario del protocolo. Referencia.
- `docs/protocolo.html` — el porqué: diagnóstico, evidencia, medición, fuentes.
- `docs/plan-grupo.html` — cómo se reparte el trabajo entre agente, miembros y admin.
- `docs/STATE.md` · `docs/DECISIONS.md` — este archivo y la bitácora de decisiones.

## Próximos pasos

- [x] Protocolo diseñado y documentado con su evidencia.
- [x] Plantilla de la página, 20 lecciones, 100 expresiones y 20 puntos de gramática.
- [x] Instrucciones del agente para el modo de solo texto.
- [x] Rampa de dificultad, checkpoints, llamada del sábado y puente al mes 2.
- [x] Empaquetar el proyecto con README como punto de entrada.
- [ ] Alojar `leccion.html` donde el agente pueda editarla y el grupo abrirla.
- [ ] Pasarle al agente la carpeta `practica-ingles/` (empieza por `README.md`).
- [ ] Confirmar o correr las horas (07:00 · 07:30 · 13:00 · 20:00).
- [ ] Que cada miembro monte su corrector privado **antes** del día 1.
- [ ] Semana 1: checkpoint 0 de cada miembro, sin preparar, guardado sin regrabar.
- [ ] Fin del mes 1: generar el mes 2 **a partir de los huecos recogidos**, no de
      una lista nueva.
- [ ] Checkpoint 1 al mes: comparar pausas interiores / 100 palabras contra el día 0.

_Última actualización: 2026-08-23_
