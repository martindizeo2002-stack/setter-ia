---
kicker: SOP
titulo: Calificación y ruteo
subtitulo: Setter IA de ADA · Doc 04 · v0.1 · 19 de octubre de 2026
---

Define cuándo un lead está calificado para la llamada, cómo lo chequea el Setter IA sin matar la conversación y adónde va cada uno. Es la excepción a la regla 4 de la biblia de setting que decidió Tincho el 19-oct-2026. El Setter IA califica y el formulario de Calendly vuelve a filtrar.

## 1. Por qué califica

| Dato | Fuente |
|---|---|
| El curioso cerró 0% y se comió 281 minutos de closer | REPORTE TOTAL, 91 calls (23-sep-2026) |
| El decisor que no estaba tumbó al menos 8 ventas y se preguntó en solo 6 de 90 llamadas | REPORTE TOTAL |
| De 30 objeciones de plata, 16 fueron "la tengo trabada" y 14 "el capital se lo come el programa" | REPORTE TOTAL |
| Cuando el closer pregunta capital y liquidez antes del minuto 15, el compromiso llega a 46%. A medias, 17% | REPORTE TOTAL |
| El volumen de conversaciones va a crecer y el closer no puede recibir curiosos | Tincho, 19-oct |

> **Cómo califica** · Sobre hechos y no sobre sentimientos. Después de dar valor, es decir después de la explicación o el ranteo y del caso, nunca antes. Con marco consultivo, "para ver si te puedo ayudar en serio". Nunca con "estás 100% comprometido", "cómo te ves en 9 meses" ni "cuánto ganás", que según la biblia matan el chat.

## 2. CVCU, qué se chequea

| Letra | Qué se chequea | Cuándo | Cómo |
|---|---|---|---|
| C, capital | Cuánto tiene para arrancar, si está disponible y si es suyo | Fase 5 | Pregunta directa |
| V, visión | Qué quiere lograr. Si da un número por mes, mejor | Fase 3A, o fase 5 en el carril B | La pregunta del guion |
| C, contexto y dolor | A qué se dedica, si opera o no, qué le pasa hoy y quién decide | Fases 1 a 3, y el decisor en la fase 5 | Lo que cuenta, más la pregunta del decisor |
| U, urgencia | Si quiere arrancar ahora o más adelante | Toda la charla | Se lee de cómo habla. Si no queda claro, se pregunta una vez |

El umbral es de 500 USD disponibles (decisión de Tincho, 19-oct). Disponible quiere decir en la mano o liberable en 7 días como máximo.

## 3. Las preguntas

Capital en el carril A, versión A:

```
perfecto
para ver si te puedo ayudar en serio necesito entender dos cosas
con cuanto capital contarias para arrancar? y esa plata la tenes disponible o depende de algo?
```

Capital en el carril A, versión B, con rangos:

```
perfecto
para ver si te puedo ayudar en serio necesito entender dos cosas
para arrancar contarias con menos de 500 dolares, entre 500 y 2000 o mas? y esa plata la tenes disponible?
```

Capital en el carril B:

```
perfecto
para ver si te puedo ayudar en serio necesito entender dos cosas
con cuanto capital estas operando hoy? y cuanto te gustaria estar generando por mes?
```

Decisor, en los dos carriles:

```
y la decision de meterte de lleno en esto la tomas vos o la charlas con alguien?
```

Si decide con otra persona:

```
perfecto, podrian estar los dos en la llamada? asi les queda claro a los dos
```

Si esquiva el capital, una sola vez:

```
no hace falta el numero exacto, es para saber que camino tiene sentido para vos
estarias mas cerca de 500 dolares, de 1000 o de mas?
```

Urgencia, solo si no quedó clara:

```
y esto lo querias arrancar ahora o mas adelante?
```

> **Las preguntas se miden** · La calificación es una fase más. Su tasa de respuesta se mide desde el día 1, y la versión A corre contra la B hasta tener N de 200 antes de elegir.

## 4. Señales que la IA lee sin preguntar

### Arquetipos

| Arquetipo | Cómo habla | Cierre en llamada | Qué hace la IA |
|---|---|---|---|
| Atrapado sin tiempo | "laburo todo el dia", "no tengo tiempo para nada", "quiero algo que me de libertad" | 71% | Califica normal. Caso de alguien con poco tiempo |
| Arbitrajista con techo | "vengo operando pero no crece", "en 2 semanas hice 7 dolares", "no consigo clientes" | 46%, mejor ticket | Carril B. Score A si tiene 2000 o más |
| Refugiado, plata parada | "tengo plata parada", "no se donde ponerla" | 43%, el ticket más alto | Score A si tiene 2000 o más |
| Estancado | "se lo que hay que hacer pero no el orden", "me mareo" | 39% | Califica normal |
| Comerciante sin caja | "la plata la tengo en mercaderia" | 40% | Mira bien la disponibilidad |
| Caída, perdió el ingreso | "me echaron", "me quede sin laburo", "quiero salir del pozo" | 21%, el más frecuente en DM | B con flag si tiene 500 disponibles. Si no, C. Si es precario, D |
| Quemado | "ya hice cursos", "me estafaron", "sirvo para esto?" | 17% | B con flag. El caso tiene que traer prueba concreta |
| Curioso | "solo me informo", "problemas no tengo", "con lo que tengo vivo bien" | 0% | C |

Las tasas son de compromiso sobre 90 leads del REPORTE TOTAL (sección 3.5).

### Los 8 perfiles del roleplay

| Perfil | Señal en el chat | Ruta |
|---|---|---|
| 1. Dice que tiene la plata pero no es suya | "plata tengo", y después aparece que es del padre o es su colchón | C |
| 2. Se informa en mal momento | "vengo a informarme", "de aca a un mes", hoy tiene otro gasto grande | C con recontacto |
| 3. No decide solo | Nombra a la pareja, al socio o al padre sin que le pregunten | B si se suma a la llamada. Si no, B condicionado |
| 4. Comparador | "estoy evaluando opciones", "sin apuro" | C con recontacto |
| 5. Experto que ya opera | Habla de OTC, apelaciones o verificado desde el arranque | A o B por el carril B, con flag de no explicar lo básico |
| 6. Perfil de oro | Vio videos, ya opera o tiene el capital, decide solo y quiere arrancar ya | A, sin sobrepreguntar |
| 7. Frustrado con capital prestado | Se critica a sí mismo y la plata es prestada, con miedo a perderla | B condicionado con flag |
| 8. Emocional que parece que no cierra | "hoy no tengo la plata comoda", pero tiene cómo juntarla y la quiere ya | B con flag emocional |

Fuente. entrenamiento/roleplay-cualificacion.md.

## 5. El score y adónde va cada uno

| Score | Cuándo | Adónde va |
|---|---|---|
| A, prioridad | 2000 USD o más disponibles. Decide solo o trae al que decide. Quiere arrancar ahora | Pitch y calendario, con flag prioridad |
| B, calificado | 500 USD o más disponibles en 7 días. Decide solo o trae al que decide. No dijo "más adelante" | Pitch y calendario |
| B condicionado | Cumple el capital pero hay un flag. Decisor que no se suma, no declaró el capital, capital prestado, sin objetivo o caída con el capital justo | Pitch y calendario. El flag va al closer |
| C, nurturing | Menos de 500, plata trabada más de 7 días, solo se informa, compara sin apuro o no tiene dolor | Ruta C del doc 01, con fecha de recontacto |
| D, descalificado | Menor de 18, situación precaria, spam o agresión | Ruta D del doc 01 y doc 15 |

### Casos especiales

| Situación | Qué hace la IA |
|---|---|
| Plata trabada que se libera en 7 días o menos (plazo fijo, un cobro, una indemnización) | B, con flag y la fecha |
| Plata trabada por más de 7 días | C, con recontacto en esa fecha |
| Esquiva el capital incluso después de la pregunta con rangos | B condicionado con flag "no declaró capital". Filtra el formulario |
| La plata es de otro y ese otro decide | C, salvo que el que decide se sume a la llamada |
| Busca algo 100% pasivo o con ganancia fija | Se aclara una vez que es un trabajo con tiempo y criterio. Si insiste, C |
| Contradice algo que dijo antes | Se toma el dato más conservador y va flag al closer |
| Pide la llamada sin contestar la calificación | Se le hace igual la pregunta de capital, corta. Si no contesta, B condicionado |

> **Lo que la IA nunca hace al calificar** · No sugiere pedir prestado, vender algo ni usar el fondo de emergencia. No le dice si le alcanza o no para el programa, porque el precio es del closer. No pregunta cuánto gana ni cuánto ahorró. No juzga la situación del lead.

## 6. Doble filtro con el formulario de Calendly

El formulario vuelve a preguntar lo duro. Así, el lead que llega al calendario por otro camino también pasa por el filtro. Esta es la propuesta para el formulario de dvtt-4hj-xjv, que se configura en la T5.

| Pregunta | Opciones |
|---|---|
| Con cuánto capital contás para arrancar | Menos de 500 USD · 500 a 1.000 · 1.000 a 2.000 · 2.000 a 5.000 · Más de 5.000 |
| Esa plata la tenés disponible hoy | Sí · Se libera en menos de 7 días · Depende de algo más |
| Quién toma la decisión | Yo solo · Con mi pareja o socio, que viene a la llamada · Con alguien que no puede venir |
| Hoy operás P2P | No, arrancaría de cero · Empecé hace poco · Sí, con clientes propios |
| Tu situación laboral | En relación de dependencia · Monotributista · Responsable inscripto · Sin trabajo · Estudiante |
| WhatsApp | Texto libre |

Si el formulario contradice lo que dijo en el chat, va flag al closer. Quien marque menos de 500 en el formulario no tendría que poder agendar. Eso se resuelve con el routing en la T5.

## 7. Lo que registra la IA

| Campo | Valores |
|---|---|
| carril | A o B |
| arquetipo | atrapado, techo, refugiado, estancado, comerciante, caida, quemado, curioso u otro |
| cvcu_capital | El rango que declaró |
| cvcu_disponible | si, en 7 dias, trabado con fecha, no |
| cvcu_decisor | solo, con otro que viene, con otro que no viene |
| cvcu_objetivo | Lo que dijo el lead, con número si lo dio |
| cvcu_urgencia | ahora, mas adelante, sin dato |
| score | A, B, B condicionado, C o D |
| flags | Lista corta para el closer |
| motivo | Por qué quedó en C o D |
| recontacto | Fecha, para los C |

Con estos campos se arma el resumen para el closer (doc 16) y se calculan las métricas (doc 21).

## 8. Cómo se mide

| Métrica | Para qué sirve |
|---|---|
| Tasa de respuesta a la pregunta de capital y a la de decisor | Saber si la calificación frena el chat |
| Reparto de scores A, B, C y D | Ver cuánto filtra |
| Agendas que el closer confirma como calificadas | Falsos positivos. La IA dejó pasar a alguien que no estaba |
| Leads C que vuelven y compran | Falsos negativos. La IA frenó a alguien que sí estaba |
| Show-up y cierre por score | Si A cierra más que B, el score sirve |
