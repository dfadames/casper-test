# Month 1 plan

Twelve sessions: Monday, Wednesday and Friday for four weeks. Everything you post
comes from this file. **You never write content yourself.**

## How the month is built

Each weekday has its own fixed activity, so nobody has to decide anything.

| Day | Activity | What people do |
|---|---|---|
| Monday | **Speaking** | The block: the same topic five times in a row |
| Wednesday | **Vocabulary** | Ten new expressions and a timed sprint |
| Friday | **Writing** | Write against the clock, then speak on the same topic |

All three end the same way: the grammar trap, the quick round and the wrap-up. The
vocabulary and writing sessions also close with two minutes of speaking, so a whole
week never goes by without anyone opening their mouth.

**Nobody studies every day.** Twelve sessions a month. The dose that worked in the
research is small — twelve narrations were enough — and here people do twenty. The
programmes that failed are the high-volume ones.

## How the demand climbs

| Week | Speaking | Writing |
|---|---|---|
| 1 | Narrative · 90s | 200 words |
| 2 | Descriptive · 2 min | 250 words |
| 3 | Explanatory · 2 min | 275 words |
| 4 | Argumentative · 2 min | 300 words |

Narrating is the cheapest: the order of events holds up anyone who stalls. Describing
takes that support away. Explaining demands precision. Arguing demands taking a
position and conceding a point at once, which is the hardest thing to formulate.

**Sessions 1 and 12: checkpoint.** The same two-minute recording, unprepared, at the
start and at the end of the month. It is the only thing that will say whether the
month was worth it.

## Who grades

Each person's own AI, not you. The page carries the prompt in every session. It gives
back a score out of ten and two things to fix, and that goes straight into the report.

You **record the score and never comment on it**.

## What happens after session 12

Month 2 comes from the gaps you collected, not from another list. When you close
session 12, give each person their full list of "got stuck on" lines, exactly as they
wrote them.

---

## What you do

Only Monday, Wednesday and Friday. Nothing on the other days.

### 07:00 · Update the page

Open `leccion.html`, find the block marked `EDITABLE BLOCK`, paste the session
object **right before** the line `];` and add a comma at the end of the previous
object. Save. **Do not touch anything else in the file.** Do not delete old sessions:
the route, the review and the sprint all use them.

Open the page after saving. If you see the notice "This session didn't load", the
paste went wrong. It is almost always a missing comma.

### 07:30 · Morning message

Copy the session's message and replace `{LINK}` with the page address.

### 13:00 · Quick round

Copy the quick-round message. **Do not post the answers** and do not correct anyone.

### 20:00 · Wrap-up

Copy the wrap-up message and record what each person reports. The page builds the
report for them with a button.

Fridays: the weekly summary. Saturdays: the call notice.

---

## What you never do

- **Never correct anyone's English.** Not the quick round, not the reports, not even if asked.
- **Never comment on the AI scores.** Record them and move on.
- **Never post the quick-round answers.**
- **Never invent sessions, topics or examples.** If the plan runs out, say so.
- **Never rewrite the messages.**
- **Never praise in general terms**, and never mention pronunciation or filled pauses.
- **Never rank people.**
- **Never post on Tuesday, Thursday or Sunday.**

---

## What you record

| Field | Values |
|---|---|
| Main activity | rounds 0–5, or sprint N/18, or essay yes/no |
| AI score | 1 to 10, plus the fix line |
| Expressions | seen / total |
| Trap | yes / no |
| Quick round | correct / total |
| Gap | the text exactly as written |

The gaps are the most valuable thing you collect. Keep them whole: don't fix the
spelling, don't translate them, don't summarise them.

---

---

# Session 1 · Week 1 · Monday

| | |
|---|---|
| **Activity** | Speaking |
| **Focus** | Just produce. Today it only matters that all five rounds happen. |
| **Trap** | Age takes BE, not HAVE |
| **Topic** | Tell the story of a time you were completely wrong about someone. |
| **Format** | 5 rounds of 90s |
| **Checkpoint** | 0 |

### Object to paste into the page

```js
  {
    "dia": 1,
    "semana": 1,
    "diaSemana": "Monday",
    "tipo": "habla",
    "foco": "Just produce. Today it only matters that all five rounds happen.",
    "porque": "This is the exercise that carries the most weight. Repeating the same topic is the only thing that, when measured, improves your speaking on new topics.",
    "checkpoint": 0,
    "diccionario": [
      {
        "es": "El problema es que no me avisaron a tiempo.",
        "en": "The thing is, they didn't tell me in time.",
        "chunk": "the thing is",
        "nota": ""
      },
      {
        "es": "Depende de cuánta gente venga.",
        "en": "It depends on how many people show up.",
        "chunk": "it depends on",
        "nota": "depends ON. Never 'depends of'."
      },
      {
        "es": "Déjame pensarlo un segundo.",
        "en": "Let me think for a second.",
        "chunk": "let me think for a second",
        "nota": ""
      },
      {
        "es": "Buena pregunta, nunca lo había pensado.",
        "en": "That's a good question — I'd never thought about it.",
        "chunk": "that's a good question",
        "nota": ""
      },
      {
        "es": "Lo que quiero decir es que no vale la pena.",
        "en": "What I'm trying to say is it's not worth it.",
        "chunk": "what I'm trying to say is",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "Age takes BE, not HAVE",
      "mal": "I have 30 years old.",
      "bien": "I'm 30 years old.",
      "explica": "In Spanish you *have* years. In English you *are* them. The same goes for hunger, thirst, cold, heat, fear and being right: 'I'm hungry', 'I'm cold', 'I'm right'.",
      "ejemplos": [
        {
          "es": "Tengo 34 años.",
          "en": "I'm 34 years old."
        },
        {
          "es": "Tengo mucha hambre.",
          "en": "I'm really hungry."
        },
        {
          "es": "Tienes razón.",
          "en": "You're right."
        }
      ]
    },
    "cierre": null,
    "bloque": {
      "tema": "Tell the story of a time you were completely wrong about someone.",
      "pista": "Past perfect: 'I had assumed…', 'it turned out…'.",
      "rondas": 5,
      "minutos": 1.5
    },
    "sprint": null,
    "ensayo": null,
    "reto": [
      {
        "es": "El problema es que no me avisaron a tiempo.",
        "en": "The thing is, they didn't tell me in time."
      },
      {
        "es": "Depende de cuánta gente venga.",
        "en": "It depends on how many people show up."
      },
      {
        "es": "Déjame pensarlo un segundo.",
        "en": "Let me think for a second."
      },
      {
        "es": "Buena pregunta, nunca lo había pensado.",
        "en": "That's a good question — I'd never thought about it."
      },
      {
        "es": "Lo que quiero decir es que no vale la pena.",
        "en": "What I'm trying to say is it's not worth it."
      }
    ],
    "retoOrigen": "Reinforcing today's material",
    "modo": "Narrativo"
  },
```

### Morning message · 07:30

```
Session 1 — speaking

Just produce. Today it only matters that all five rounds happen.

Here: {LINK}

FIRST THING TODAY: checkpoint. Record two minutes on this prompt,
with nothing prepared.

  "Tell me about your last week. Go through it in order, and include
   one thing that went wrong and what you did about it."

Save it as checkpoint-0 and DON'T listen to it. It's today's snapshot.
The value is in comparing it a month from now.

The block: the same topic 5 times, 90s each.

"Tell the story of a time you were completely wrong about someone."

Leave your AI listening on the last round. The page has the prompt.

Also: today's trap (age takes be, not have).
Quick round here at 1pm.
```

### Quick round · 13:00

_Reinforcing today's material. Do NOT post the answers._

```
Quick round, session 1

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. El problema es que no me avisaron a tiempo.
2. Depende de cuánta gente venga.
3. Déjame pensarlo un segundo.
4. Buena pregunta, nunca lo había pensado.
5. Lo que quiero decir es que no vale la pena.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 1 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 1 · Week 1 · Speaking
  Block: __/5 rounds
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 2 · Week 1 · Wednesday

| | |
|---|---|
| **Activity** | Vocabulary |
| **Focus** | Expressions that buy you time — the ones that let you keep going when you stall. |
| **Trap** | A specific past time takes the past simple, not the present perfect |
| **Sprint** | 15 sentences in 60s |

### Object to paste into the page

```js
  {
    "dia": 2,
    "semana": 1,
    "diaSemana": "Wednesday",
    "tipo": "vocabulario",
    "foco": "Expressions that buy you time — the ones that let you keep going when you stall.",
    "porque": "Knowing an expression is useless if it takes you two seconds to find it. The sprint trains speed, not memory.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Te lo pongo así: nadie quedó contento.",
        "en": "Let me put it this way: nobody walked away happy.",
        "chunk": "let me put it this way",
        "nota": ""
      },
      {
        "es": "Iba a decir que sí, pero mejor no.",
        "en": "I was going to say yes, but I'd rather not.",
        "chunk": "I was going to say",
        "nota": ""
      },
      {
        "es": "Es raro, ¿me entiendes?",
        "en": "It's weird, you know what I mean?",
        "chunk": "you know what I mean",
        "nota": ""
      },
      {
        "es": "De hecho, ya lo había hecho antes.",
        "en": "As a matter of fact, I'd already done it before.",
        "chunk": "as a matter of fact",
        "nota": ""
      },
      {
        "es": "Espérate un segundo, déjame revisar.",
        "en": "Hang on a second, let me check.",
        "chunk": "hang on a second",
        "nota": ""
      },
      {
        "es": "No creo que sea buena idea.",
        "en": "I don't think it's a good idea.",
        "chunk": "I don't think it's",
        "nota": "English negates the main verb: 'I don't think it is', not 'I think it isn't'."
      },
      {
        "es": "Que yo sepa, todavía no han decidido.",
        "en": "As far as I know, they haven't decided yet.",
        "chunk": "as far as I know",
        "nota": ""
      },
      {
        "es": "Sinceramente, no me convenció.",
        "en": "To be honest, it didn't convince me.",
        "chunk": "to be honest",
        "nota": ""
      },
      {
        "es": "Yo diría que unas tres semanas.",
        "en": "I'd say about three weeks.",
        "chunk": "I'd say",
        "nota": ""
      },
      {
        "es": "Me parece que se está complicando solo.",
        "en": "It seems to me that he's making it harder than it is.",
        "chunk": "it seems to me that",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "A specific past time takes the past simple, not the present perfect",
      "mal": "I have seen him yesterday.",
      "bien": "I saw him yesterday.",
      "explica": "Spanish uses 'he visto' with past time markers. English does not allow it. If you say when it happened — yesterday, last week, in 2020, ago — use the past simple. With no marker, the perfect works fine.",
      "ejemplos": [
        {
          "es": "Terminé el informe ayer.",
          "en": "I finished the report yesterday."
        },
        {
          "es": "Ya lo terminé.",
          "en": "I've already finished it."
        },
        {
          "es": "Hablé con él la semana pasada.",
          "en": "I spoke to him last week."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "Talk for two minutes about anything you like, using at least five of today's expressions."
    },
    "bloque": null,
    "sprint": {
      "segundos": 60,
      "items": [
        {
          "es": "El problema es que no me avisaron a tiempo.",
          "en": "The thing is, they didn't tell me in time."
        },
        {
          "es": "Depende de cuánta gente venga.",
          "en": "It depends on how many people show up."
        },
        {
          "es": "Déjame pensarlo un segundo.",
          "en": "Let me think for a second."
        },
        {
          "es": "Buena pregunta, nunca lo había pensado.",
          "en": "That's a good question — I'd never thought about it."
        },
        {
          "es": "Lo que quiero decir es que no vale la pena.",
          "en": "What I'm trying to say is it's not worth it."
        },
        {
          "es": "Te lo pongo así: nadie quedó contento.",
          "en": "Let me put it this way: nobody walked away happy."
        },
        {
          "es": "Iba a decir que sí, pero mejor no.",
          "en": "I was going to say yes, but I'd rather not."
        },
        {
          "es": "Es raro, ¿me entiendes?",
          "en": "It's weird, you know what I mean?"
        },
        {
          "es": "De hecho, ya lo había hecho antes.",
          "en": "As a matter of fact, I'd already done it before."
        },
        {
          "es": "Espérate un segundo, déjame revisar.",
          "en": "Hang on a second, let me check."
        },
        {
          "es": "No creo que sea buena idea.",
          "en": "I don't think it's a good idea."
        },
        {
          "es": "Que yo sepa, todavía no han decidido.",
          "en": "As far as I know, they haven't decided yet."
        },
        {
          "es": "Sinceramente, no me convenció.",
          "en": "To be honest, it didn't convince me."
        },
        {
          "es": "Yo diría que unas tres semanas.",
          "en": "I'd say about three weeks."
        },
        {
          "es": "Me parece que se está complicando solo.",
          "en": "It seems to me that he's making it harder than it is."
        }
      ]
    },
    "ensayo": null,
    "reto": [
      {
        "es": "El problema es que no me avisaron a tiempo.",
        "en": "The thing is, they didn't tell me in time."
      },
      {
        "es": "Depende de cuánta gente venga.",
        "en": "It depends on how many people show up."
      },
      {
        "es": "Déjame pensarlo un segundo.",
        "en": "Let me think for a second."
      },
      {
        "es": "Buena pregunta, nunca lo había pensado.",
        "en": "That's a good question — I'd never thought about it."
      },
      {
        "es": "Lo que quiero decir es que no vale la pena.",
        "en": "What I'm trying to say is it's not worth it."
      }
    ],
    "retoOrigen": "Review of session 1",
    "modo": "Vocabulario"
  },
```

### Morning message · 07:30

```
Session 2 — vocabulary

Expressions that buy you time — the ones that let you keep going when you stall.

Here: {LINK}

Vocabulary today: 10 new expressions and a 60-second
sprint over the ones you've already seen. The sprint gives you a number.
That number should climb over the month.

Close by talking for two minutes using today's expressions.

Also: today's trap (a specific past time takes the past simple, not the present perfect).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of session 1. Do NOT post the answers._

```
Quick round, session 2

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. El problema es que no me avisaron a tiempo.
2. Depende de cuánta gente venga.
3. Déjame pensarlo un segundo.
4. Buena pregunta, nunca lo había pensado.
5. Lo que quiero decir es que no vale la pena.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 2 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 2 · Week 1 · Vocabulary
  Sprint: __ of 15 in 60s
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/10
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 3 · Week 1 · Friday

| | |
|---|---|
| **Activity** | Writing |
| **Focus** | Write what you cannot yet say. |
| **Trap** | DEPEND takes ON |
| **Essay** | 200 words in 25 min |

### Object to paste into the page

```js
  {
    "dia": 3,
    "semana": 1,
    "diaSemana": "Friday",
    "tipo": "ensayo",
    "foco": "Write what you cannot yet say.",
    "porque": "When you write, you have time to build the sentence properly. The distance between that and what comes out when you speak is exactly your gap.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "No tengo ni idea de dónde quedó.",
        "en": "I have no idea where it ended up.",
        "chunk": "I have no idea",
        "nota": ""
      },
      {
        "es": "No estoy tan seguro de eso.",
        "en": "I'm not so sure about that.",
        "chunk": "I'm not so sure about that",
        "nota": ""
      },
      {
        "es": "Por mi parte, el tema está cerrado.",
        "en": "As far as I'm concerned, the matter is closed.",
        "chunk": "as far as I'm concerned",
        "nota": ""
      },
      {
        "es": "No hay duda de que funcionó.",
        "en": "There's no doubt that it worked.",
        "chunk": "there's no doubt that",
        "nota": ""
      },
      {
        "es": "Yo tiendo a pensar que es al revés.",
        "en": "I tend to think it's the other way around.",
        "chunk": "I tend to think",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "DEPEND takes ON",
      "mal": "It depends of the weather.",
      "bien": "It depends on the weather.",
      "explica": "Almost everyone gets this one wrong and it is very audible. The whole preposition family shifts: depend ON, consist OF, think ABOUT, dream OF, insist ON, and arrive AT or IN — never 'arrive to'.",
      "ejemplos": [
        {
          "es": "Depende de ti.",
          "en": "It depends on you."
        },
        {
          "es": "Llegué a la oficina tarde.",
          "en": "I arrived at the office late."
        },
        {
          "es": "Estaba pensando en eso.",
          "en": "I was thinking about that."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "After writing, talk for two minutes on the same topic. Do not re-read what you wrote."
    },
    "bloque": null,
    "sprint": null,
    "ensayo": {
      "consigna": "Write about a decision you made that you would make differently now. What did you think at the time, and what changed?",
      "palabras": 200,
      "minutos": 25
    },
    "reto": [
      {
        "es": "Te lo pongo así: nadie quedó contento.",
        "en": "Let me put it this way: nobody walked away happy."
      },
      {
        "es": "Iba a decir que sí, pero mejor no.",
        "en": "I was going to say yes, but I'd rather not."
      },
      {
        "es": "Es raro, ¿me entiendes?",
        "en": "It's weird, you know what I mean?"
      },
      {
        "es": "De hecho, ya lo había hecho antes.",
        "en": "As a matter of fact, I'd already done it before."
      },
      {
        "es": "Espérate un segundo, déjame revisar.",
        "en": "Hang on a second, let me check."
      }
    ],
    "retoOrigen": "Review of session 2",
    "modo": "Narrativo"
  },
```

### Morning message · 07:30

```
Session 3 — writing

Write what you cannot yet say.

Here: {LINK}

Writing today: 200 words in 25 minutes,
dictionary closed.

"Write about a decision you made that you would make differently now. What did you think at the time, and what changed?"

Then two minutes talking on the same topic, without re-reading what you wrote.
That difference is the exercise.

Also: today's trap (depend takes on).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of session 2. Do NOT post the answers._

```
Quick round, session 3

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Te lo pongo así: nadie quedó contento.
2. Iba a decir que sí, pero mejor no.
3. Es raro, ¿me entiendes?
4. De hecho, ya lo había hecho antes.
5. Espérate un segundo, déjame revisar.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 3 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 3 · Week 1 · Writing
  Essay: 200 words
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 4 · Week 2 · Monday

| | |
|---|---|
| **Activity** | Speaking |
| **Focus** | Hold a description together with no timeline to lean on. |
| **Trap** | PEOPLE is plural |
| **Topic** | Describe the neighborhood you grew up in, to someone who has never been to Colombia. |
| **Format** | 5 rounds of 2 min |

### Object to paste into the page

```js
  {
    "dia": 4,
    "semana": 2,
    "diaSemana": "Monday",
    "tipo": "habla",
    "foco": "Hold a description together with no timeline to lean on.",
    "porque": "This is the exercise that carries the most weight. Repeating the same topic is the only thing that, when measured, improves your speaking on new topics.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Lo que quiero decir es otra cosa.",
        "en": "What I mean is something different.",
        "chunk": "what I mean is",
        "nota": ""
      },
      {
        "es": "En otras palabras, no van a pagar.",
        "en": "In other words, they're not going to pay.",
        "chunk": "in other words",
        "nota": ""
      },
      {
        "es": "¿Se entiende lo que digo?",
        "en": "Does that make sense?",
        "chunk": "does that make sense",
        "nota": ""
      },
      {
        "es": "Tiene que ver con cómo lo plantearon.",
        "en": "It has to do with the way they framed it.",
        "chunk": "it has to do with",
        "nota": ""
      },
      {
        "es": "Fue en marzo, o más bien a finales de febrero.",
        "en": "It was in March — or rather, late February.",
        "chunk": "or rather",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "PEOPLE is plural",
      "mal": "The people is angry.",
      "bien": "The people are angry.",
      "explica": "'People' is already plural: never 'peoples', never 'the people is'. Same with police. The reverse trap: news, advice and information are uncountable and take a singular verb with no 's'.",
      "ejemplos": [
        {
          "es": "La gente está cansada.",
          "en": "People are tired."
        },
        {
          "es": "Las noticias son malas.",
          "en": "The news is bad."
        },
        {
          "es": "Me dio un buen consejo.",
          "en": "He gave me some good advice."
        }
      ]
    },
    "cierre": null,
    "bloque": {
      "tema": "Describe the neighborhood you grew up in, to someone who has never been to Colombia.",
      "pista": "Past habit: 'we used to…'. Careful with 'used to' against 'be used to'.",
      "rondas": 5,
      "minutos": 2
    },
    "sprint": null,
    "ensayo": null,
    "reto": [
      {
        "es": "No tengo ni idea de dónde quedó.",
        "en": "I have no idea where it ended up."
      },
      {
        "es": "No estoy tan seguro de eso.",
        "en": "I'm not so sure about that."
      },
      {
        "es": "El problema es que no me avisaron a tiempo.",
        "en": "The thing is, they didn't tell me in time."
      },
      {
        "es": "Depende de cuánta gente venga.",
        "en": "It depends on how many people show up."
      },
      {
        "es": "Por mi parte, el tema está cerrado.",
        "en": "As far as I'm concerned, the matter is closed."
      }
    ],
    "retoOrigen": "Review of sessions 3 and 1",
    "modo": "Descriptivo"
  },
```

### Morning message · 07:30

```
Session 4 — speaking

Hold a description together with no timeline to lean on.

Here: {LINK}

The block: the same topic 5 times, 2 min each.

"Describe the neighborhood you grew up in, to someone who has never been to Colombia."

Leave your AI listening on the last round. The page has the prompt.

Also: today's trap (people is plural).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 3 and 1. Do NOT post the answers._

```
Quick round, session 4

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. No tengo ni idea de dónde quedó.
2. No estoy tan seguro de eso.
3. El problema es que no me avisaron a tiempo.
4. Depende de cuánta gente venga.
5. Por mi parte, el tema está cerrado.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 4 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 4 · Week 2 · Speaking
  Block: __/5 rounds
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 5 · Week 2 · Wednesday

| | |
|---|---|
| **Activity** | Vocabulary |
| **Focus** | Modality: obligation, habit and probability without translating word for word. |
| **Trap** | One negative per sentence |
| **Sprint** | 18 sentences in 60s |

### Object to paste into the page

```js
  {
    "dia": 5,
    "semana": 2,
    "diaSemana": "Wednesday",
    "tipo": "vocabulario",
    "foco": "Modality: obligation, habit and probability without translating word for word.",
    "porque": "Knowing an expression is useless if it takes you two seconds to find it. The sprint trains speed, not memory.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Lo que estoy diciendo es que nadie revisó.",
        "en": "The point I'm making is that nobody checked.",
        "chunk": "the point I'm making is",
        "nota": ""
      },
      {
        "es": "Dicho de otra manera, salió más caro.",
        "en": "To put it another way, it ended up costing more.",
        "chunk": "to put it another way",
        "nota": ""
      },
      {
        "es": "¿Cómo lo digo? No fue exactamente un error.",
        "en": "How can I say this — it wasn't exactly a mistake.",
        "chunk": "how can I say this",
        "nota": ""
      },
      {
        "es": "No sé cómo explicarlo, pero se sentía mal.",
        "en": "I don't know how to explain it, but it felt wrong.",
        "chunk": "I don't know how to explain it",
        "nota": ""
      },
      {
        "es": "Es un poco incómodo, si me entiendes.",
        "en": "It's a little awkward, if you know what I mean.",
        "chunk": "if you know what I mean",
        "nota": ""
      },
      {
        "es": "No tienes que venir si no quieres.",
        "en": "You don't have to come if you don't want to.",
        "chunk": "you don't have to",
        "nota": "'You mustn't' means it is forbidden. 'You don't have to' means it is optional. Not the same thing."
      },
      {
        "es": "Lo único que tienes que hacer es avisarme.",
        "en": "All you have to do is let me know.",
        "chunk": "all you have to do is",
        "nota": ""
      },
      {
        "es": "Se supone que debo entregarlo hoy.",
        "en": "I'm supposed to hand it in today.",
        "chunk": "I'm supposed to",
        "nota": ""
      },
      {
        "es": "Mejor me voy ya.",
        "en": "I'd better get going.",
        "chunk": "I'd better",
        "nota": ""
      },
      {
        "es": "Tengo que salir en diez minutos.",
        "en": "I've got to leave in ten minutes.",
        "chunk": "I've got to",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "One negative per sentence",
      "mal": "I don't know nothing.",
      "bien": "I don't know anything.",
      "explica": "Spanish stacks negatives. English cancels them out. If the verb is already negative, what follows takes ANY-: anything, anyone, anywhere, ever. Either you negate the verb or you use nothing, nobody, never — never both.",
      "ejemplos": [
        {
          "es": "No dije nada.",
          "en": "I didn't say anything."
        },
        {
          "es": "No conozco a nadie ahí.",
          "en": "I don't know anyone there."
        },
        {
          "es": "Nunca he estado allá.",
          "en": "I've never been there."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "Talk for two minutes about anything you like, using at least five of today's expressions."
    },
    "bloque": null,
    "sprint": {
      "segundos": 60,
      "items": [
        {
          "es": "El problema es que no me avisaron a tiempo.",
          "en": "The thing is, they didn't tell me in time."
        },
        {
          "es": "Depende de cuánta gente venga.",
          "en": "It depends on how many people show up."
        },
        {
          "es": "Déjame pensarlo un segundo.",
          "en": "Let me think for a second."
        },
        {
          "es": "Buena pregunta, nunca lo había pensado.",
          "en": "That's a good question — I'd never thought about it."
        },
        {
          "es": "Lo que quiero decir es que no vale la pena.",
          "en": "What I'm trying to say is it's not worth it."
        },
        {
          "es": "Te lo pongo así: nadie quedó contento.",
          "en": "Let me put it this way: nobody walked away happy."
        },
        {
          "es": "Iba a decir que sí, pero mejor no.",
          "en": "I was going to say yes, but I'd rather not."
        },
        {
          "es": "Es raro, ¿me entiendes?",
          "en": "It's weird, you know what I mean?"
        },
        {
          "es": "De hecho, ya lo había hecho antes.",
          "en": "As a matter of fact, I'd already done it before."
        },
        {
          "es": "Espérate un segundo, déjame revisar.",
          "en": "Hang on a second, let me check."
        },
        {
          "es": "No creo que sea buena idea.",
          "en": "I don't think it's a good idea."
        },
        {
          "es": "Que yo sepa, todavía no han decidido.",
          "en": "As far as I know, they haven't decided yet."
        },
        {
          "es": "Sinceramente, no me convenció.",
          "en": "To be honest, it didn't convince me."
        },
        {
          "es": "Yo diría que unas tres semanas.",
          "en": "I'd say about three weeks."
        },
        {
          "es": "Me parece que se está complicando solo.",
          "en": "It seems to me that he's making it harder than it is."
        },
        {
          "es": "No tengo ni idea de dónde quedó.",
          "en": "I have no idea where it ended up."
        },
        {
          "es": "No estoy tan seguro de eso.",
          "en": "I'm not so sure about that."
        },
        {
          "es": "Por mi parte, el tema está cerrado.",
          "en": "As far as I'm concerned, the matter is closed."
        }
      ]
    },
    "ensayo": null,
    "reto": [
      {
        "es": "Lo que quiero decir es otra cosa.",
        "en": "What I mean is something different."
      },
      {
        "es": "En otras palabras, no van a pagar.",
        "en": "In other words, they're not going to pay."
      },
      {
        "es": "Te lo pongo así: nadie quedó contento.",
        "en": "Let me put it this way: nobody walked away happy."
      },
      {
        "es": "Iba a decir que sí, pero mejor no.",
        "en": "I was going to say yes, but I'd rather not."
      },
      {
        "es": "¿Se entiende lo que digo?",
        "en": "Does that make sense?"
      }
    ],
    "retoOrigen": "Review of sessions 4 and 2",
    "modo": "Vocabulario"
  },
```

### Morning message · 07:30

```
Session 5 — vocabulary

Modality: obligation, habit and probability without translating word for word.

Here: {LINK}

Vocabulary today: 10 new expressions and a 60-second
sprint over the ones you've already seen. The sprint gives you a number.
That number should climb over the month.

Close by talking for two minutes using today's expressions.

Also: today's trap (one negative per sentence).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 4 and 2. Do NOT post the answers._

```
Quick round, session 5

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Lo que quiero decir es otra cosa.
2. En otras palabras, no van a pagar.
3. Te lo pongo así: nadie quedó contento.
4. Iba a decir que sí, pero mejor no.
5. ¿Se entiende lo que digo?

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 5 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 5 · Week 2 · Vocabulary
  Sprint: __ of 18 in 60s
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/10
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 6 · Week 2 · Friday

| | |
|---|---|
| **Activity** | Writing |
| **Focus** | Concrete detail instead of general adjectives. |
| **Trap** | AGREE is a verb, not an adjective |
| **Essay** | 250 words in 25 min |

### Object to paste into the page

```js
  {
    "dia": 6,
    "semana": 2,
    "diaSemana": "Friday",
    "tipo": "ensayo",
    "foco": "Concrete detail instead of general adjectives.",
    "porque": "When you write, you have time to build the sentence properly. The distance between that and what comes out when you speak is exactly your gap.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Ya que estoy aquí, aprovecho y lo hago.",
        "en": "Since I'm here, I might as well do it.",
        "chunk": "I might as well",
        "nota": ""
      },
      {
        "es": "Deberías decírselo tú mismo.",
        "en": "You ought to tell him yourself.",
        "chunk": "you ought to",
        "nota": ""
      },
      {
        "es": "Necesito conseguir eso antes del viernes.",
        "en": "I need to get that before Friday.",
        "chunk": "I need to get",
        "nota": ""
      },
      {
        "es": "No hace falta que te disculpes.",
        "en": "There's no need to apologize.",
        "chunk": "there's no need to",
        "nota": ""
      },
      {
        "es": "Se suponía que esto iba a ser rápido.",
        "en": "This was meant to be quick.",
        "chunk": "it was meant to be",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "AGREE is a verb, not an adjective",
      "mal": "I'm agree with you.",
      "bien": "I agree with you.",
      "explica": "'Agree' already means 'to be in agreement', so it takes no 'be'. The same trap hits other verbs that Spanish builds with 'estar': I need, I disagree, I depend.",
      "ejemplos": [
        {
          "es": "Estoy de acuerdo contigo.",
          "en": "I agree with you."
        },
        {
          "es": "No estoy de acuerdo con eso.",
          "en": "I disagree with that."
        },
        {
          "es": "Estoy de acuerdo hasta cierto punto.",
          "en": "I agree to a certain extent."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "After writing, talk for two minutes on the same topic. Do not re-read what you wrote."
    },
    "bloque": null,
    "sprint": null,
    "ensayo": {
      "consigna": "Describe a place that matters to you — without saying why it matters. Let the details do that work.",
      "palabras": 250,
      "minutos": 25
    },
    "reto": [
      {
        "es": "Lo que estoy diciendo es que nadie revisó.",
        "en": "The point I'm making is that nobody checked."
      },
      {
        "es": "Dicho de otra manera, salió más caro.",
        "en": "To put it another way, it ended up costing more."
      },
      {
        "es": "No tengo ni idea de dónde quedó.",
        "en": "I have no idea where it ended up."
      },
      {
        "es": "No estoy tan seguro de eso.",
        "en": "I'm not so sure about that."
      },
      {
        "es": "¿Cómo lo digo? No fue exactamente un error.",
        "en": "How can I say this — it wasn't exactly a mistake."
      }
    ],
    "retoOrigen": "Review of sessions 5 and 3",
    "modo": "Descriptivo"
  },
```

### Morning message · 07:30

```
Session 6 — writing

Concrete detail instead of general adjectives.

Here: {LINK}

Writing today: 250 words in 25 minutes,
dictionary closed.

"Describe a place that matters to you — without saying why it matters. Let the details do that work."

Then two minutes talking on the same topic, without re-reading what you wrote.
That difference is the exercise.

Also: today's trap (agree is a verb, not an adjective).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 5 and 3. Do NOT post the answers._

```
Quick round, session 6

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Lo que estoy diciendo es que nadie revisó.
2. Dicho de otra manera, salió más caro.
3. No tengo ni idea de dónde quedó.
4. No estoy tan seguro de eso.
5. ¿Cómo lo digo? No fue exactamente un error.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 6 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 6 · Week 2 · Writing
  Essay: 250 words
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 7 · Week 3 · Monday

| | |
|---|---|
| **Activity** | Speaking |
| **Focus** | Explain something precisely, and repair yourself as you go. |
| **Trap** | Questions need an auxiliary |
| **Topic** | Explain how something you use every day actually works — pick something you only half understand. |
| **Format** | 5 rounds of 2 min |

### Object to paste into the page

```js
  {
    "dia": 7,
    "semana": 3,
    "diaSemana": "Monday",
    "tipo": "habla",
    "foco": "Explain something precisely, and repair yourself as you go.",
    "porque": "This is the exercise that carries the most weight. Repeating the same topic is the only thing that, when measured, improves your speaking on new topics.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Antes trabajaba de noche.",
        "en": "I used to work nights.",
        "chunk": "I used to",
        "nota": "A past habit that has stopped. Always followed by the infinitive."
      },
      {
        "es": "Ya estoy acostumbrado.",
        "en": "I'm used to it by now.",
        "chunk": "I'm used to it",
        "nota": "The pair that catches everyone: 'used to + infinitive' is a past habit; 'be used to + -ing' is being accustomed to something."
      },
      {
        "es": "Voy a intentarlo otra vez.",
        "en": "I'm going to give it another shot.",
        "chunk": "I'm going to",
        "nota": ""
      },
      {
        "es": "Lo que vamos a hacer es empezar por lo fácil.",
        "en": "What we're going to do is start with the easy part.",
        "chunk": "what we're going to do is",
        "nota": ""
      },
      {
        "es": "Estoy a punto de terminar.",
        "en": "I'm about to finish.",
        "chunk": "I'm about to",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "Questions need an auxiliary",
      "mal": "Where you work?",
      "bien": "Where do you work?",
      "explica": "Spanish asks a question by changing intonation. English needs do, does or did — or the verb be, or a modal. Without it the question sounds broken, even when people understand you.",
      "ejemplos": [
        {
          "es": "¿Dónde trabajas?",
          "en": "Where do you work?"
        },
        {
          "es": "¿A qué hora llegó?",
          "en": "What time did he arrive?"
        },
        {
          "es": "¿Por qué dijiste eso?",
          "en": "Why did you say that?"
        }
      ]
    },
    "cierre": null,
    "bloque": {
      "tema": "Explain how something you use every day actually works — pick something you only half understand.",
      "pista": "Honest vagueness: 'something like that', 'it has to do with…'.",
      "rondas": 5,
      "minutos": 2
    },
    "sprint": null,
    "ensayo": null,
    "reto": [
      {
        "es": "Ya que estoy aquí, aprovecho y lo hago.",
        "en": "Since I'm here, I might as well do it."
      },
      {
        "es": "Deberías decírselo tú mismo.",
        "en": "You ought to tell him yourself."
      },
      {
        "es": "Lo que quiero decir es otra cosa.",
        "en": "What I mean is something different."
      },
      {
        "es": "En otras palabras, no van a pagar.",
        "en": "In other words, they're not going to pay."
      },
      {
        "es": "El problema es que no me avisaron a tiempo.",
        "en": "The thing is, they didn't tell me in time."
      }
    ],
    "retoOrigen": "Review of sessions 6, 4 and 1",
    "modo": "Explicativo"
  },
```

### Morning message · 07:30

```
Session 7 — speaking

Explain something precisely, and repair yourself as you go.

Here: {LINK}

The block: the same topic 5 times, 2 min each.

"Explain how something you use every day actually works — pick something you only half understand."

Leave your AI listening on the last round. The page has the prompt.

Also: today's trap (questions need an auxiliary).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 6, 4 and 1. Do NOT post the answers._

```
Quick round, session 7

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Ya que estoy aquí, aprovecho y lo hago.
2. Deberías decírselo tú mismo.
3. Lo que quiero decir es otra cosa.
4. En otras palabras, no van a pagar.
5. El problema es que no me avisaron a tiempo.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 7 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 7 · Week 3 · Speaking
  Block: __/5 rounds
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 8 · Week 3 · Wednesday

| | |
|---|---|
| **Activity** | Vocabulary |
| **Focus** | Phrasal verbs — where translating straight from Spanish always fails. |
| **Trap** | SINCE marks the start, FOR marks the length |
| **Sprint** | 18 sentences in 60s |

### Object to paste into the page

```js
  {
    "dia": 8,
    "semana": 3,
    "diaSemana": "Wednesday",
    "tipo": "vocabulario",
    "foco": "Phrasal verbs — where translating straight from Spanish always fails.",
    "porque": "Knowing an expression is useless if it takes you two seconds to find it. The sprint trains speed, not memory.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "No pude llegar a tiempo.",
        "en": "I wasn't able to get there on time.",
        "chunk": "I wasn't able to",
        "nota": ""
      },
      {
        "es": "Es probable que llueva.",
        "en": "It's likely to rain.",
        "chunk": "it's likely to",
        "nota": ""
      },
      {
        "es": "Tarde o temprano se va a dar cuenta.",
        "en": "He's bound to find out sooner or later.",
        "chunk": "he's bound to",
        "nota": ""
      },
      {
        "es": "Logré arreglarlo al final.",
        "en": "I managed to fix it in the end.",
        "chunk": "I managed to",
        "nota": "'Manage to' means to pull something off with effort. It is not 'manejar'."
      },
      {
        "es": "No me puedo dar el lujo de perder otro día.",
        "en": "I can't afford to lose another day.",
        "chunk": "I can't afford to",
        "nota": ""
      },
      {
        "es": "Eran como veinte personas, o algo así.",
        "en": "There were about twenty people, or something like that.",
        "chunk": "or something like that",
        "nota": ""
      },
      {
        "es": "Traje cuadernos, lápices y cosas así.",
        "en": "I brought notebooks, pencils and things like that.",
        "chunk": "and things like that",
        "nota": ""
      },
      {
        "es": "Reuniones, informes, ese tipo de cosas.",
        "en": "Meetings, reports, that sort of thing.",
        "chunk": "that sort of thing",
        "nota": ""
      },
      {
        "es": "Estuvo como raro.",
        "en": "It was kind of weird.",
        "chunk": "kind of",
        "nota": ""
      },
      {
        "es": "Fue un poco un desastre.",
        "en": "It was a bit of a mess.",
        "chunk": "a bit of a",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "SINCE marks the start, FOR marks the length",
      "mal": "I live here since three years.",
      "bien": "I've lived here for three years.",
      "explica": "Spanish 'desde hace' splits into two words in English. SINCE takes a moment: since 2020, since Monday, since I moved. FOR takes a period: for three years, for a while. And it goes with the present perfect, not the present simple.",
      "ejemplos": [
        {
          "es": "Trabajo aquí desde marzo.",
          "en": "I've worked here since March."
        },
        {
          "es": "Llevo dos horas esperando.",
          "en": "I've been waiting for two hours."
        },
        {
          "es": "No lo veo desde el año pasado.",
          "en": "I haven't seen him since last year."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "Talk for two minutes about anything you like, using at least five of today's expressions."
    },
    "bloque": null,
    "sprint": {
      "segundos": 60,
      "items": [
        {
          "es": "El problema es que no me avisaron a tiempo.",
          "en": "The thing is, they didn't tell me in time."
        },
        {
          "es": "Buena pregunta, nunca lo había pensado.",
          "en": "That's a good question — I'd never thought about it."
        },
        {
          "es": "Iba a decir que sí, pero mejor no.",
          "en": "I was going to say yes, but I'd rather not."
        },
        {
          "es": "Espérate un segundo, déjame revisar.",
          "en": "Hang on a second, let me check."
        },
        {
          "es": "Sinceramente, no me convenció.",
          "en": "To be honest, it didn't convince me."
        },
        {
          "es": "No tengo ni idea de dónde quedó.",
          "en": "I have no idea where it ended up."
        },
        {
          "es": "No hay duda de que funcionó.",
          "en": "There's no doubt that it worked."
        },
        {
          "es": "En otras palabras, no van a pagar.",
          "en": "In other words, they're not going to pay."
        },
        {
          "es": "Fue en marzo, o más bien a finales de febrero.",
          "en": "It was in March — or rather, late February."
        },
        {
          "es": "¿Cómo lo digo? No fue exactamente un error.",
          "en": "How can I say this — it wasn't exactly a mistake."
        },
        {
          "es": "No tienes que venir si no quieres.",
          "en": "You don't have to come if you don't want to."
        },
        {
          "es": "Mejor me voy ya.",
          "en": "I'd better get going."
        },
        {
          "es": "Deberías decírselo tú mismo.",
          "en": "You ought to tell him yourself."
        },
        {
          "es": "Se suponía que esto iba a ser rápido.",
          "en": "This was meant to be quick."
        },
        {
          "es": "Voy a intentarlo otra vez.",
          "en": "I'm going to give it another shot."
        },
        {
          "es": "No pude llegar a tiempo.",
          "en": "I wasn't able to get there on time."
        },
        {
          "es": "Logré arreglarlo al final.",
          "en": "I managed to fix it in the end."
        },
        {
          "es": "Traje cuadernos, lápices y cosas así.",
          "en": "I brought notebooks, pencils and things like that."
        }
      ]
    },
    "ensayo": null,
    "reto": [
      {
        "es": "Antes trabajaba de noche.",
        "en": "I used to work nights."
      },
      {
        "es": "Ya estoy acostumbrado.",
        "en": "I'm used to it by now."
      },
      {
        "es": "Lo que estoy diciendo es que nadie revisó.",
        "en": "The point I'm making is that nobody checked."
      },
      {
        "es": "Dicho de otra manera, salió más caro.",
        "en": "To put it another way, it ended up costing more."
      },
      {
        "es": "Te lo pongo así: nadie quedó contento.",
        "en": "Let me put it this way: nobody walked away happy."
      }
    ],
    "retoOrigen": "Review of sessions 7, 5 and 2",
    "modo": "Vocabulario"
  },
```

### Morning message · 07:30

```
Session 8 — vocabulary

Phrasal verbs — where translating straight from Spanish always fails.

Here: {LINK}

Vocabulary today: 10 new expressions and a 60-second
sprint over the ones you've already seen. The sprint gives you a number.
That number should climb over the month.

Close by talking for two minutes using today's expressions.

Also: today's trap (since marks the start, for marks the length).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 7, 5 and 2. Do NOT post the answers._

```
Quick round, session 8

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Antes trabajaba de noche.
2. Ya estoy acostumbrado.
3. Lo que estoy diciendo es que nadie revisó.
4. Dicho de otra manera, salió más caro.
5. Te lo pongo así: nadie quedó contento.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 8 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 8 · Week 3 · Vocabulary
  Sprint: __ of 18 in 60s
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/10
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 9 · Week 3 · Friday

| | |
|---|---|
| **Activity** | Writing |
| **Focus** | Precision without jargon. |
| **Trap** | After a preposition comes -ING, never the infinitive |
| **Essay** | 275 words in 30 min |

### Object to paste into the page

```js
  {
    "dia": 9,
    "semana": 3,
    "diaSemana": "Friday",
    "tipo": "ensayo",
    "foco": "Precision without jargon.",
    "porque": "When you write, you have time to build the sentence properly. The distance between that and what comes out when you speak is exactly your gap.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Más o menos lo mismo.",
        "en": "More or less the same thing.",
        "chunk": "more or less",
        "nota": ""
      },
      {
        "es": "Como una hora.",
        "en": "An hour or so.",
        "chunk": "an hour or so",
        "nota": ""
      },
      {
        "es": "Un par de días.",
        "en": "A couple of days.",
        "chunk": "a couple of",
        "nota": ""
      },
      {
        "es": "Llámalo error, descuido, o lo que sea.",
        "en": "Call it a mistake, an oversight, or whatever.",
        "chunk": "or whatever",
        "nota": ""
      },
      {
        "es": "Bastante gente se quejó.",
        "en": "Quite a lot of people complained.",
        "chunk": "quite a lot of",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "After a preposition comes -ING, never the infinitive",
      "mal": "I'm interested in learn more.",
      "bien": "I'm interested in learning more.",
      "explica": "Every preposition takes -ing: interested IN doing, good AT doing, instead OF doing, before or after doing, look forward TO doing. That last one fools everyone, because the 'to' looks like an infinitive and is not.",
      "ejemplos": [
        {
          "es": "Estoy pensando en cambiar de trabajo.",
          "en": "I'm thinking about changing jobs."
        },
        {
          "es": "Tengo ganas de verlos.",
          "en": "I'm looking forward to seeing them."
        },
        {
          "es": "En vez de esperar, llamé.",
          "en": "Instead of waiting, I called."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "After writing, talk for two minutes on the same topic. Do not re-read what you wrote."
    },
    "bloque": null,
    "sprint": null,
    "ensayo": {
      "consigna": "Explain something from your work to someone outside your field. No jargon, no shortcuts.",
      "palabras": 275,
      "minutos": 30
    },
    "reto": [
      {
        "es": "No pude llegar a tiempo.",
        "en": "I wasn't able to get there on time."
      },
      {
        "es": "Es probable que llueva.",
        "en": "It's likely to rain."
      },
      {
        "es": "Ya que estoy aquí, aprovecho y lo hago.",
        "en": "Since I'm here, I might as well do it."
      },
      {
        "es": "Deberías decírselo tú mismo.",
        "en": "You ought to tell him yourself."
      },
      {
        "es": "No tengo ni idea de dónde quedó.",
        "en": "I have no idea where it ended up."
      }
    ],
    "retoOrigen": "Review of sessions 8, 6 and 3",
    "modo": "Explicativo"
  },
```

### Morning message · 07:30

```
Session 9 — writing

Precision without jargon.

Here: {LINK}

Writing today: 275 words in 30 minutes,
dictionary closed.

"Explain something from your work to someone outside your field. No jargon, no shortcuts."

Then two minutes talking on the same topic, without re-reading what you wrote.
That difference is the exercise.

Also: today's trap (after a preposition comes -ing, never the infinitive).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 8, 6 and 3. Do NOT post the answers._

```
Quick round, session 9

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. No pude llegar a tiempo.
2. Es probable que llueva.
3. Ya que estoy aquí, aprovecho y lo hago.
4. Deberías decírselo tú mismo.
5. No tengo ni idea de dónde quedó.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 9 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 9 · Week 3 · Writing
  Essay: 275 words
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 10 · Week 4 · Monday

| | |
|---|---|
| **Activity** | Speaking |
| **Focus** | Take a side and concede a point without losing the thread. |
| **Trap** | ACTUALLY does not mean 'actualmente' |
| **Topic** | Is it better to be very good at one thing, or decent at many? Argue one side. |
| **Format** | 5 rounds of 2 min |

### Object to paste into the page

```js
  {
    "dia": 10,
    "semana": 4,
    "diaSemana": "Monday",
    "tipo": "habla",
    "foco": "Take a side and concede a point without losing the thread.",
    "porque": "This is the exercise that carries the most weight. Repeating the same topic is the only thing that, when measured, improves your speaking on new topics.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Al final terminé quedándome.",
        "en": "I ended up staying.",
        "chunk": "I ended up",
        "nota": "Always followed by -ing."
      },
      {
        "es": "Se me ocurrió una idea mejor.",
        "en": "I came up with a better idea.",
        "chunk": "I came up with",
        "nota": ""
      },
      {
        "es": "Resultó que estaba equivocado.",
        "en": "It turned out I was wrong.",
        "chunk": "it turned out",
        "nota": ""
      },
      {
        "es": "Me encontré con esto por casualidad.",
        "en": "I came across this by accident.",
        "chunk": "I came across",
        "nota": ""
      },
      {
        "es": "Al final todo salió bien.",
        "en": "It all worked out in the end.",
        "chunk": "it worked out",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "ACTUALLY does not mean 'actualmente'",
      "mal": "Actually I'm working in a bank.",
      "bien": "Currently I'm working at a bank.",
      "explica": "'Actually' means 'in fact'. 'Actualmente' is currently, or right now. It is the most common false friend there is, and it flips the meaning of your sentence without anyone stopping to correct you.",
      "ejemplos": [
        {
          "es": "En realidad, no me gustó.",
          "en": "Actually, I didn't like it."
        },
        {
          "es": "Actualmente vivo en Bogotá.",
          "en": "I currently live in Bogotá."
        },
        {
          "es": "De hecho, ya lo había hecho.",
          "en": "Actually, I'd already done it."
        }
      ]
    },
    "cierre": null,
    "bloque": {
      "tema": "Is it better to be very good at one thing, or decent at many? Argue one side.",
      "pista": "Concession: 'I take your point, but…', 'on the other hand'.",
      "rondas": 5,
      "minutos": 2
    },
    "sprint": null,
    "ensayo": null,
    "reto": [
      {
        "es": "Más o menos lo mismo.",
        "en": "More or less the same thing."
      },
      {
        "es": "Como una hora.",
        "en": "An hour or so."
      },
      {
        "es": "Antes trabajaba de noche.",
        "en": "I used to work nights."
      },
      {
        "es": "Ya estoy acostumbrado.",
        "en": "I'm used to it by now."
      },
      {
        "es": "Lo que quiero decir es otra cosa.",
        "en": "What I mean is something different."
      }
    ],
    "retoOrigen": "Review of sessions 9, 7 and 4",
    "modo": "Argumentativo"
  },
```

### Morning message · 07:30

```
Session 10 — speaking

Take a side and concede a point without losing the thread.

Here: {LINK}

The block: the same topic 5 times, 2 min each.

"Is it better to be very good at one thing, or decent at many? Argue one side."

Leave your AI listening on the last round. The page has the prompt.

Also: today's trap (actually does not mean 'actualmente').
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 9, 7 and 4. Do NOT post the answers._

```
Quick round, session 10

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Más o menos lo mismo.
2. Como una hora.
3. Antes trabajaba de noche.
4. Ya estoy acostumbrado.
5. Lo que quiero decir es otra cosa.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 10 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 10 · Week 4 · Speaking
  Block: __/5 rounds
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 11 · Week 4 · Wednesday

| | |
|---|---|
| **Activity** | Vocabulary |
| **Focus** | Contrast and closing. How to link two ideas, and how to finish. |
| **Trap** | The false friends you will hit most often |
| **Sprint** | 18 sentences in 60s |

### Object to paste into the page

```js
  {
    "dia": 11,
    "semana": 4,
    "diaSemana": "Wednesday",
    "tipo": "vocabulario",
    "foco": "Contrast and closing. How to link two ideas, and how to finish.",
    "porque": "Knowing an expression is useless if it takes you two seconds to find it. The sprint trains speed, not memory.",
    "checkpoint": null,
    "diccionario": [
      {
        "es": "Ya lo solucioné.",
        "en": "I sorted it out.",
        "chunk": "I sorted it out",
        "nota": ""
      },
      {
        "es": "Todavía no entiendo cómo funciona.",
        "en": "I still haven't figured out how it works.",
        "chunk": "to figure out",
        "nota": ""
      },
      {
        "es": "Me enteré ayer.",
        "en": "I found out yesterday.",
        "chunk": "I found out",
        "nota": ""
      },
      {
        "es": "Alguien señaló que faltaba una parte.",
        "en": "Someone pointed out that a part was missing.",
        "chunk": "someone pointed out",
        "nota": ""
      },
      {
        "es": "Se nos acabó el tiempo.",
        "en": "We ran out of time.",
        "chunk": "we ran out of",
        "nota": ""
      },
      {
        "es": "Sigamos con lo nuestro.",
        "en": "Let's get on with it.",
        "chunk": "let's get on with it",
        "nota": ""
      },
      {
        "es": "No pienso aguantar eso.",
        "en": "I'm not going to put up with that.",
        "chunk": "to put up with",
        "nota": ""
      },
      {
        "es": "Se salió con la suya.",
        "en": "He got away with it.",
        "chunk": "he got away with it",
        "nota": ""
      },
      {
        "es": "Después nos ponemos al día.",
        "en": "Let's catch up later.",
        "chunk": "to catch up",
        "nota": ""
      },
      {
        "es": "Me cuesta seguirle el ritmo.",
        "en": "I struggle to keep up with him.",
        "chunk": "to keep up with",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "The false friends you will hit most often",
      "mal": "I assisted to the meeting and realized the report.",
      "bien": "I attended the meeting and wrote the report.",
      "explica": "Assist means to help — 'asistir a' is attend. Realize means to notice — 'realizar' is do, make or carry out. Support means to back — 'soportar' is put up with. Sensible means level-headed — 'sensible' is sensitive.",
      "ejemplos": [
        {
          "es": "Asistí a la reunión.",
          "en": "I attended the meeting."
        },
        {
          "es": "Me di cuenta después.",
          "en": "I realized afterwards."
        },
        {
          "es": "No soporto ese ruido.",
          "en": "I can't put up with that noise."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "Talk for two minutes about anything you like, using at least five of today's expressions."
    },
    "bloque": null,
    "sprint": {
      "segundos": 60,
      "items": [
        {
          "es": "El problema es que no me avisaron a tiempo.",
          "en": "The thing is, they didn't tell me in time."
        },
        {
          "es": "Lo que quiero decir es que no vale la pena.",
          "en": "What I'm trying to say is it's not worth it."
        },
        {
          "es": "De hecho, ya lo había hecho antes.",
          "en": "As a matter of fact, I'd already done it before."
        },
        {
          "es": "Sinceramente, no me convenció.",
          "en": "To be honest, it didn't convince me."
        },
        {
          "es": "No estoy tan seguro de eso.",
          "en": "I'm not so sure about that."
        },
        {
          "es": "Lo que quiero decir es otra cosa.",
          "en": "What I mean is something different."
        },
        {
          "es": "Fue en marzo, o más bien a finales de febrero.",
          "en": "It was in March — or rather, late February."
        },
        {
          "es": "No sé cómo explicarlo, pero se sentía mal.",
          "en": "I don't know how to explain it, but it felt wrong."
        },
        {
          "es": "Se supone que debo entregarlo hoy.",
          "en": "I'm supposed to hand it in today."
        },
        {
          "es": "Deberías decírselo tú mismo.",
          "en": "You ought to tell him yourself."
        },
        {
          "es": "Antes trabajaba de noche.",
          "en": "I used to work nights."
        },
        {
          "es": "Estoy a punto de terminar.",
          "en": "I'm about to finish."
        },
        {
          "es": "Logré arreglarlo al final.",
          "en": "I managed to fix it in the end."
        },
        {
          "es": "Reuniones, informes, ese tipo de cosas.",
          "en": "Meetings, reports, that sort of thing."
        },
        {
          "es": "Como una hora.",
          "en": "An hour or so."
        },
        {
          "es": "Al final terminé quedándome.",
          "en": "I ended up staying."
        },
        {
          "es": "Al final todo salió bien.",
          "en": "It all worked out in the end."
        },
        {
          "es": "Alguien señaló que faltaba una parte.",
          "en": "Someone pointed out that a part was missing."
        }
      ]
    },
    "ensayo": null,
    "reto": [
      {
        "es": "Al final terminé quedándome.",
        "en": "I ended up staying."
      },
      {
        "es": "Se me ocurrió una idea mejor.",
        "en": "I came up with a better idea."
      },
      {
        "es": "No pude llegar a tiempo.",
        "en": "I wasn't able to get there on time."
      },
      {
        "es": "Es probable que llueva.",
        "en": "It's likely to rain."
      },
      {
        "es": "Lo que estoy diciendo es que nadie revisó.",
        "en": "The point I'm making is that nobody checked."
      }
    ],
    "retoOrigen": "Review of sessions 10, 8 and 5",
    "modo": "Vocabulario"
  },
```

### Morning message · 07:30

```
Session 11 — vocabulary

Contrast and closing. How to link two ideas, and how to finish.

Here: {LINK}

Vocabulary today: 10 new expressions and a 60-second
sprint over the ones you've already seen. The sprint gives you a number.
That number should climb over the month.

Close by talking for two minutes using today's expressions.

Also: today's trap (the false friends you will hit most often).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 10, 8 and 5. Do NOT post the answers._

```
Quick round, session 11

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Al final terminé quedándome.
2. Se me ocurrió una idea mejor.
3. No pude llegar a tiempo.
4. Es probable que llueva.
5. Lo que estoy diciendo es que nadie revisó.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 11 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 11 · Week 4 · Vocabulary
  Sprint: __ of 18 in 60s
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/10
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

# Session 12 · Week 4 · Friday

| | |
|---|---|
| **Activity** | Writing |
| **Focus** | A position and a concession, in writing. |
| **Trap** | MAKE creates, DO performs |
| **Essay** | 300 words in 30 min |
| **Checkpoint** | 1 |

### Object to paste into the page

```js
  {
    "dia": 12,
    "semana": 4,
    "diaSemana": "Friday",
    "tipo": "ensayo",
    "foco": "A position and a concession, in writing.",
    "porque": "When you write, you have time to build the sentence properly. The distance between that and what comes out when you speak is exactly your gap.",
    "checkpoint": 1,
    "diccionario": [
      {
        "es": "Lo voy a averiguar.",
        "en": "I'll look into it.",
        "chunk": "I'll look into it",
        "nota": ""
      },
      {
        "es": "Tengo ganas de que llegue.",
        "en": "I'm looking forward to it.",
        "chunk": "looking forward to",
        "nota": "Followed by -ing, not the infinitive: 'looking forward to seeing you'."
      },
      {
        "es": "Yo me encargo.",
        "en": "I'll take care of it.",
        "chunk": "I'll take care of it",
        "nota": ""
      },
      {
        "es": "Hay que deshacerse de eso.",
        "en": "We need to get rid of that.",
        "chunk": "to get rid of",
        "nota": ""
      },
      {
        "es": "Todavía no me decido.",
        "en": "I haven't made up my mind yet.",
        "chunk": "to make up my mind",
        "nota": ""
      }
    ],
    "trampa": {
      "titulo": "MAKE creates, DO performs",
      "mal": "I need to make my homework.",
      "bien": "I need to do my homework.",
      "explica": "DO for tasks and activities: do homework, do the dishes, do business, do someone a favour, do your best. MAKE for whatever produces something new: make a decision, make a mistake, make money, make sense, make an effort. Spanish uses 'hacer' for both.",
      "ejemplos": [
        {
          "es": "Cometí un error.",
          "en": "I made a mistake."
        },
        {
          "es": "¿Me haces un favor?",
          "en": "Can you do me a favor?"
        },
        {
          "es": "No tiene sentido.",
          "en": "It doesn't make sense."
        }
      ]
    },
    "cierre": {
      "min": 2,
      "consigna": "After writing, talk for two minutes on the same topic. Do not re-read what you wrote."
    },
    "bloque": null,
    "sprint": null,
    "ensayo": {
      "consigna": "Should companies be allowed to require people back in the office? Argue one side, and concede one real point to the other.",
      "palabras": 300,
      "minutos": 30
    },
    "reto": [
      {
        "es": "Ya lo solucioné.",
        "en": "I sorted it out."
      },
      {
        "es": "Todavía no entiendo cómo funciona.",
        "en": "I still haven't figured out how it works."
      },
      {
        "es": "Más o menos lo mismo.",
        "en": "More or less the same thing."
      },
      {
        "es": "Como una hora.",
        "en": "An hour or so."
      },
      {
        "es": "Ya que estoy aquí, aprovecho y lo hago.",
        "en": "Since I'm here, I might as well do it."
      }
    ],
    "retoOrigen": "Review of sessions 11, 9 and 6",
    "modo": "Argumentativo"
  },
```

### Morning message · 07:30

```
Session 12 — writing

A position and a concession, in writing.

Here: {LINK}

Last session of the month, and there's a checkpoint. The SAME prompt as
session 1, with the week that just went by.

  "Tell me about your last week. Go through it in order, and include
   one thing that went wrong and what you did about it."

Nothing prepared. And now yes: play it back to back with the first one.

Writing today: 300 words in 30 minutes,
dictionary closed.

"Should companies be allowed to require people back in the office? Argue one side, and concede one real point to the other."

Then two minutes talking on the same topic, without re-reading what you wrote.
That difference is the exercise.

Also: today's trap (make creates, do performs).
Quick round here at 1pm.
```

### Quick round · 13:00

_Review of sessions 11, 9 and 6. Do NOT post the answers._

```
Quick round, session 12

In English, fast, nothing looked up. If you're unsure, send the unsure version anyway.

1. Ya lo solucioné.
2. Todavía no entiendo cómo funciona.
3. Más o menos lo mismo.
4. Como una hora.
5. Ya que estoy aquí, aprovecho y lo hago.

The answers are on the page. Reveal them AFTER you've written yours.
```

### Wrap-up · 20:00

```
Session 12 wrap-up. The page builds your report:
open the last step and hit "Copy for WhatsApp".

It looks like this:

  Session 12 · Week 4 · Writing
  Essay: 300 words
  Spoken close: yes/no
  AI score: __/10
  To fix: (what the AI said)
  Expressions: __/5
  Trap: yes/no
  Quick round: __/5
  Got stuck on: (what you wanted to say and couldn't)

That last line is the one that matters. Send it even if you did nothing else.
```


---

## Recurring messages

### Friday 20:00 · weekly summary

```
Week {W} closed.

Sessions completed: {name} {n}/3 · {name} {n}/3 · {name} {n}/3
Gaps collected: {n}

Tomorrow at 10am is the call. Half an hour, in English.

If you missed sessions this week, it's fine. The dose that works is small.
What doesn't work is disappearing.
```

_AI scores don't go here. They're for each person to compare against themselves._

### Saturday 09:30 · the call

```
Call in 30 minutes. Half an hour, all in English.

  5 min — everyone tells their week, two minutes max
  15 min — Monday's topic, but live
  10 min — free

One rule: if you stall, don't switch to Spanish. Talk around the word and keep going.
"How can I say this…", "the thing is…", "what I mean is…"

It's the only live half hour of the week, and it's worth several sessions.
```

### Session 12, after the wrap-up · handing back the gaps

```
{name}, these are the {n} gaps you reported this month, exactly as you wrote them:

{full list}

This list is the material for month 2. Send it to {admin} so the next four weeks
get built from your real failures.
```

### Fixed replies

| If this happens | You say |
|---|---|
| Someone asks you to correct their English | "That goes to your AI, with the prompt on the page. I keep the rhythm." |
| Someone asks whether their score is good | "I don't judge it. It's there so you can compare yourself in three weeks." |
| Someone asks for the quick-round answers | "They're on the page, after you write yours." |
| Someone did nothing today | "Just send the 'got stuck on' line. That makes the session count." |
| Someone apologises for their level | "Report it anyway. Half a session counts; an unreported one doesn't." |
| Someone asks if they can send audio | "I don't handle audio. You do it on your own and report back." |
| Someone asks why there's no session today | "We study every other day: Monday, Wednesday, Friday." |
| Someone has been missing for days | Nothing. Keep posting the wrap-up with whoever reported. |
| The plan runs out | "Month 1 is done. {admin}, we need month 2." |

---

## Welcome message

```
This group has one job: to stop us freezing in the middle of a sentence in English.

Before we start, open the page and read the "Method" tab. Three minutes, and it
explains why it's built this way. The "Route" tab shows the twelve sessions.

We study every other day: Monday, Wednesday, Friday. Twelve sessions this month.
That isn't laziness dressed up — the dose that works in the research is small, and
the programmes that fail are the high-volume ones.

Each day has its activity:
  Monday    — speaking. The same topic five times in a row.
  Wednesday — vocabulary. Ten expressions and a timed sprint.
  Friday    — writing. Against the clock, then you speak it.

Saturdays at 10am, a half-hour call in English.

Four things worth knowing up front:

1. Speaking happens OUT LOUD, on your own, wherever. I don't take audio: you
   report back to me. It runs on trust.
2. Your own AI grades you, not me. The page carries the prompt. You leave it
   listening and it gives you a score and two things to fix.
3. I don't correct English and I don't comment on scores. I keep the rhythm.
4. Listening to and reading English does not improve your speaking. The measured
   effect is close to zero. That's why here we produce instead of consuming.

Today and in the last session there's a checkpoint: two minutes recorded on the
same prompt, unprepared. It's the only thing that will tell us if this worked.

Half a session counts. An unreported one doesn't.
```
