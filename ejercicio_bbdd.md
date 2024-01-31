# Ejercicio sobre bases de datos. Construye una base de datos a partir de un texto descriptivo.


> + **_Versión_**: 2023-2024
> + **_Asignatura (titulación)_**: Ciclo de gestión del dato: ecoinformática (máster conservación, gestión y restauración de la biodiversidad. UGR) 
> + **_Autor_**:  María Suárez Muñoz (bv2sumum@uco.es) y Curro Bonet García



## Objetivos del ejercicio

Esta actividad tiene los siguientes objetivos de aprendizaje:

+ Afianzar el conocimiento adquirido en clase sobre bases de datos relacionales.
+ Trasladar el conocimiento adquirido sobre la construcción de bases de datos a un caso de estudio concreto y real. Esto permitirá entrenar dichos conocimientos y contribuirá a que se afiancen en vuestra memoria a largo plazo. 
+ Mejorar la capacidad para recopilar, almacenar, acceder y compartir datos relevantes para analizar información ambiental.
+ Fomentar la metacognición (capacidad de tomar conciencia de cómo aprendemos). El hecho de "corregir" el ejercicio de manera conjunta permite a los estudiantes identficar sus propios errores cuando ven explícitamente los de otros compañeros. Esta habilidad es muy útil en la vida cotidiana.

## Tareas a realizar

Para practicar un poco más con la creación y construcción de bases de datos relacionales se propone un ejercicio consistente en crear una base de datos sencilla, elaborando y describiendo los pasos necesarios para ello. Para construir la base de datos podéis utilizar el conjunto de datos, el proceso o la información que os resulte más útil e interesante. Podéis pensar en información que estáis recopilando para algún trabajo de clase o vuestro TFM, en vuestra colección de arácnidos, en vuestro perfil de Spotify... Pero si no tenéis algún conjunto de datos que os resulte práctico utilizar podéis utilizar esta descripción:

*"Muestreos fitosociológicos: Se diseña un trabajo de campo que consiste en hacer muestreos fitosociológicos en una serie de puntos del territorio. En cada muestreo (caracterizado por un punto), se evalúan la presencia y abundancia de todas las especies vegetales existentes en un radio de xx m desde el centro de la parcela. La presencia de las especies se registra a través de un listado de taxones de Andalucía. Su abundancia se codifica según el criterio de Braun-Blanquet (búscalo en internet si no sabes lo que es). Cada muestreo es realizado por un equipo de personas cuyo número es variable. También es importante tener en cuenta que cada punto puede ser visitado en varias ocasiones".*

Ahora os pedimos que elaboréis:

1. Una descripción literal de vuestra base de datos. Esta descripción en forma de texto deberá explicar en detalle qué información se va a almacenar en la base de datos y qué características tiene. 

2. Un diagrama entidad-relación que muestre la estructura de vuestra base de datos. Este diagrama, en forma de imagen o esquema mostrará la estructura de la base de datos. Es probable que al elaborarlo encuentres ambigüedades en la descripción de la base de datos. Tendrás entonces que volver a la descripción y modificarla para mejorarla. Es un proceso iterativo. Identifica las entidades y los atributos importantes.

3. Una base de datos. Traduce el o los diagramas entidad-relación en una estructura de bases de datos relacional, con sus tablas y campos. Esta base de datos en formato digital reflejará la información de la descripción y el diagrama en forma de tablas y relaciones. Además podrá contener datos y consultas que muestren cómo puede servir la base de datos para responder a una pregunta concreta.

Cuando lo tengas listo comprime los archivos y súbelos al classroom. Por favor, usa este esquema para nombrar el archivo comprimido: [tu_nombre]_[tus_apellidos].zip


## Criterios de evaluación

Esta tarea tiene como objetivo que penséis, encontréis problemas y dudas sin resolver, las reflexionemos y aprendamos de ello. Por lo tanto, el producto a entregar está bastante abierto a vuestras necesidades y podrá tener distintas versiones. A modo de recomendación, resaltamos algunos de los aspectos importantes para evaluar si habéis adquirido las competencias que buscamos.

1. Descripción literal de la base de datos
	+ Descripción clara y sin ambigüedad
	+ Legibilidad y fluidez

2. Diagrama entidad-relación
	+ Identificación de entidades, atributos de la realidad que queremos modelar, así como las relaciones entre los mismos
	+ Justificación de las decisiones adoptadas

3. Base de datos
	+ Traducción de los elementos anteriores a una estructura interpretable por un gestor de bases de datos relacionales: tablas, campos, relaciones.
	+ Nivel de implementación: tablas, relaciones, datos y consultas.
	+ Identificación de dificultades encontradas. No es lo mismo no hacer algo, que no saber hacerlo poque tengo un problema o duda que me está impidiendo avanzar...


<div style="page-break-after: always; break-after: page;"></div>

| Descripción literal de la base de datos                      |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| ------------------------------------------------------------ | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Se evalúa la claridad, legibilidad y fluidez en la descripción de los datos e información a incluir en la base de datos |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | El texto no permite identificar la información que contendrá la base de datos | El texto describe la información a incorporar a la base de datos, pero presenta ambigüedades que limitan su implementación | El texto describe la información a incoporar permitiendo identificar las entidades y los atributos más relevantes. | El texto describe la información a incoporar permitiendo identificar las entidades, los atributos y las relaciones más relevantes. | El texto describe correctamente la información, facilitando la identificación de entidades, atributos y relaciones sin ambigüedad. |
| **Completitud de las entidades y sus atributos**             |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa en qué medida has identificado bien las entidades contempladas en el texto descriptivo, así como sus correspondientes atributos. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | No identificación de variables ni de atributos               | Mezcla de atributos con entidades                            | Correcta identificación de ambos conceptos                   | Identificación completa de atributos y entidades             | Incorporas conceptos y/o atributos que mejoran la base de datos |
|                                                              |             | No has identificado correctamente ni los atributos ni las entidades. | Has mezclado ambos conceptos                                 | Has diferenciado bien entre entidades y atributos, pero faltan alguno de cualquiera de ellos. | Están todos los atributos y entidades.                       | Además de considerar todos los conceptos y atributos del enunciado, lo has mejorado. |
| **Completitud de las relaciones entre entidades**            |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa en qué medida has identificado bien las relaciones entre entidades. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | No has identificado correctamente ninguna relación.          | Faltan muchas relaciones                                     | Correcta identificación de relaciones                        | Identificación completa de relaciones                        | Incorporas nuevas relaciones que mejoran la base de datos.   |
|                                                              |             |                                                              | Has incluído alguna relación, pero faltan muchas.            | Has identificado adecuadamente la mayoría de las relaciones. | Están todas las relaciones y su cardinalidad es correcta.    |                                                              |
| **Traducción del modelo entidad relación a un diagrama de bases de datos** |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa en qué medida has traducido el esquema de entidades-relaciones a un diagrama de tablas en una base de datos. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0s                                                         |
|                                                              | No entrega. | Muy incompleta traducción de entidades/atributos a tablas/campos | Incompleta asignación de entidades/atributos a tablas/campos | Correcta traducción de entidades/atributos a tablas/campos   | Traducción completa                                          | Incorporas nuevas tablas y campos que mejoran la estructura. |
|                                                              |             |                                                              | Has traducido bien algunos elementos, pero faltan muchos.    | Están realizadas correctamente casi todas las asignaciones entidad/atributo a tabla/campo. | Todas las entidades y sus atributos han sido traducidos a tablas y a campos. |                                                              |
| **Nivel de implementación**                                  |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| Se evalúa el grado de implementación de la base de datos en la herramienta. |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | Se han creado las tablas necesarias, pero faltan las relaciones | Se han creado las tablas y las relaciones entre las ellas, pero faltan algunas | Se han creado todas las tablas y relaciones necesarias       | Se han incorporado datos a las tablas                        | Se ha creado una o varias consultas que muestran el uso potencial de la base de dato |
| **Identificación de dificultades**                           |             |                                                              |                                                              |                                                              |                                                              |                                                              |
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega  | Las dificultades encontradas no están definidas, lo que limita su abordaje | Algunas dificultades han sido identificadas de forma poco precisa | Se detallan algunos problemas y dificultades encontradas en el proceso de implementación | Los problemas para una completa implementación de la base de datos están claramente definidos y acotados | Se proponen soluciones a las dificultades encontradas, aunque no lleguen a resolver el problema |



Usaré esta rúbrica para evaluar tu trabajo, pero la nota no se usará en la calificación de la asignatura.

La evaluación de este ejercicio se realizará siguiendo las siguientes fases, que se basan en la idea de re-evaluación y análisis en grupo de resultados.

+ **Primera entrega**: Los alumnos entregan el ejercicio solicitado usando el conocimiento adquirido en las sesiones teóricas.
+ **Segunda entrega**: Los alumnos entregan de nuevo el ejercicio incorporando las mejoras y soluciones a los problemas encontrados durante la primera entrega.



