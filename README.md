# Tutor Personal de Carrera Tech

Un **mega-prompt en siete capas** que convierte tu contexto real, un objetivo concreto y
un reporte de brechas en un plan de desarrollo de 30 días que cabe en el tiempo que de
verdad tienes.

No es un generador de listas de cursos. Si tu tiempo no alcanza para lo que persigues,
lo dice **antes** de presentarte el plan.

**Autor:** Jesús Armando Tapia Gallegos — [@atapia9](https://github.com/atapia9)

---

## Qué hay aquí

| Archivo | Qué es |
|---|---|
| [`plantilla-tutor.md`](./plantilla-tutor.md) | **Empieza por aquí.** La plantilla en blanco, con notas de qué poner en cada bloque y qué evitar |
| [`tutor-v1.md`](./tutor-v1.md) | La instancia del autor, completa y funcionando. Sirve como ejemplo de qué tan específico conviene ser |
| [`ejemplo-salida.md`](./ejemplo-salida.md) | Lo que produjo: un PDI de 30 días con cuatro semanas ejecutables, sin editar |

## Cómo se usa

1. Copia [`plantilla-tutor.md`](./plantilla-tutor.md) y rellena los seis bloques marcados.
2. Pega el resultado completo en la IA generativa que prefieras.
3. Guárdalo como `tutor-v1.md` en tu propio repositorio.
4. Al terminar el ciclo, actualiza **solo** el bloque de contexto y vuelve a correrlo. Esa es toda la ventaja de tenerlo por capas.

## Las siete capas, y por qué en ese orden

| # | Capa | Qué controla |
|---|---|---|
| 1 | **Persona** | Quién responde. Va primero porque tiñe todo lo demás |
| 2 | **Contexto** | Quién eres y qué restricciones tienes |
| 3 | **Base de conocimiento** | Los datos contra los que se mide el plan, etiquetados por fuente |
| 4 | **Razonamiento** | En qué orden piensa antes de concluir |
| 5 | **Patrón de salida** | La forma exacta de la respuesta, enseñada con ejemplos |
| 6 | **Restricciones** | Los límites no negociables |
| 7 | **Tarea** | El pedido, al final, para que sea lo último que lee |

## Las tres decisiones que hacen la diferencia

**La capa de límites.** Describir el tono de la persona cambia la superficie de la
respuesta; escribir lo que esa persona **se niega a hacer** cambia el contenido. Reglas
del tipo "no recomiendas otra certificación como respuesta a un problema comercial"
eliminan de un plumazo la respuesta genérica que este tipo de perfil recibe siempre.

**El paso "qué información me falta".** Dentro de la lógica de razonamiento, es el que
convierte la IA de oráculo en herramienta de investigación. En lugar de fingir certeza,
mapea lo que todavía tienes que averiguar por tu cuenta — y lo que falta casi nunca se
resuelve estudiando.

**La cláusula de honestidad.** *"Si mi tiempo es insuficiente para el plan, dilo
explícitamente antes de presentarlo."* Un tutor que siempre dice que sí no es un tutor.
En el ejemplo de este repositorio, lo primero que hizo fue avisar que 30 minutos al día
no alcanzaban para el objetivo elegido, y solo después propuso lo que sí cabía.

## Lo que este tutor NO hace

- **No sabe si tienes razón.** Trabaja con los datos que le das. Contexto desactualizado, plan coherente y equivocado.
- **No sustituye una conversación con un cliente o un reclutador.**
- **Su razonamiento visible no es una prueba.** Es una superficie de auditoría: sirve para que revises los criterios, no para confiar en que ese fue el camino real.
- **No es una frontera de seguridad.** Las reglas de la sección 6 reducen el riesgo de que un texto pegado le dé órdenes; no lo eliminan.

## De dónde salió

Es el proyecto final del reto **#7DaysOfCode de Prompt Engineering** de
[Alura Latam](https://www.alura.com.br/). Cada capa es la técnica de un día: PTC, role
prompting, few-shot, chain of thought, delimitadores y restricciones, e inyección de
contexto largo.

El proceso completo —los siete días, con los ensayos, las comparaciones y lo que salió
mal— está documentado en
[atapia9/7DaysOfCode-Prompt-Engineering](https://github.com/atapia9/7DaysOfCode-Prompt-Engineering).

## Licencia

[Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](./LICENSE).

Puedes copiarlo, adaptarlo y usarlo —incluido como material de clase— siempre que des
crédito. Atribución sugerida:

> Jesús Armando Tapia Gallegos, *Tutor Personal de Carrera Tech* (2026).
> https://github.com/atapia9/tutor-carrera-tech — CC BY 4.0
