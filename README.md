# Alexa-Skills

The following is a serie of projects of Alexa skills

# Project One : Habla con tu doggo

### Invocation
```
User say: Alexa, abre hablar con mi perro

User say: Alexa, quiero hablar con mi perro

```
### Dialogs

```
User say: Alexa, abre hablar con mi perro

Alexa : ¿ Excelente que te gustaria traducir ?

User say: ¿ Donde esta mi tarea ? , ¿ Te la comiste?

Alexa : Wof Wof WoofWoooof Wof Woof Wof
Alexa : ¿ Te gustaria traducir algo mas ?

```

### Back End Design

### Development


### Test


### Publication


# Project Two : alingo , aprende español con tu Alexa

## Invocation
```
User say: Alexa, abre alingo
User say: Alexa, abre aprende español con Alexa
User say: Alexa, open learn spanish with Alexa
```

### Dialogs

```
-------- English -------- 

User say: Alexa, open learn spanish with Alexa

Alexa : Are you ready to start learning ?

User say: Yay!

Alexa : Excelent let's start with a short vocabulary lesson: remember the most of the folowing words:
Alexa : {{  Slots Collections | Ingles-Español Vocabulary }}
Alexa : Are you ready to practice?

User say: I'm ready

Alexa : How do you say {{ Slot }} ?

User say: {{ Slot | Input del usuario }}

Alexa : Awesome! Next

Alexa : How do you say {{ Slot }} ?

User say: {{ Slot | Input del usuario }}

Alexa : Sorry it's not okey, try again.

Alexa : Excelent, lets see your score: your final score is {{ Counter }} and the words most difficult for you are : {{ Collection of Fail Slots }}

```
```
-------- ESPAÑOL -------- 

User say: Alexa, abre alingo

Alexa : ¿ Excelente Listo para empezar a aprender ?

User say: listo | de una | claro | si

Alexa : Excelente comensemos con una pequeña leccion de vocabulario: memoriza la mayor cantidad de palabras que sean posibles:
Alexa : {{ Coleccion de slots | Vocabuulario ingles-español }}
Alexa : ¿ Estas listo para practicar ?

User say: listo | de una | claro | si

Alexa : ¿ Como se dice {{ Slot }} ?

User say: {{ Slot | Input del usuario }}

Alexa : ¿ Como se dice calabaza ?

```

### Back End Design

### Development


### Test


### Publication
