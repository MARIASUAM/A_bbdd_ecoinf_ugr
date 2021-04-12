# Ejercicio sobre bases de datos. Construye una base de datos a partir de un texto descriptivo.


> + **_Versión_**: 2020-2021
> + **_Asignatura (titulación)_**: Ciclo de gestión del dato: ecoinformática (máster conservación, gestión y restauración de la biodiversidad. UGR). Curso 2020-2021
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)



## Objetivos del ejercicio

Esta actividad tiene el siguiente objetivo de aprendizaje:

Trasladar el conocimiento adquirido sobre la construcción de bases de datos a un caso de estudio concreto y real. Esto permitirá entrenar dichos conocimientos y contribuirá a que se afiancen en vuestra memoria a largo plazo. 

## Tareas a realizar

Lee atentamente el siguiente texto:

Imagina que te contratan para trabajar en la Red de Información Ambiental de Andalucía para construir una base de datos que permita almacenar información sobre un mapa de vegetación. Dicho mapa consta de dos metodologías complementarias, cada una de las cuales tiene una componente geográfica y otra alfanumérica. Son las siguientes:

+ Fotointerpretación de la vegetación: Consiste en identificar manchas de vegetación homogéneas para una serie de variables estructurales (cobertura del estrato arbóreo, arbustivo, herbáceo, porcentaje de suelo desnudo y formación vegetal). Cada fotointérprete va dibujando polígonos en un SIG y les va asignando los valores de las variables anteriores. El parámetro de densidad se estima con rangos numéricos (Ausente, 1-25%, 26-50%, 51-75% y 76-100%). La formación vegetal se obtiene de una lista de formaciones vegetales de Andalucía. También se registra el nombre de la persona que delimita cada polígono. La escala de trabajo es 1:10.000.

+ Muestreos fitosociológicos: En virtud de la caracterización espacial obtenida anteriormente, se diseña un trabajo de campo que consiste en hacer muestreos fitosociológicos en una serie de puntos del territorio. En cada muestreo (caracterizado por un punto), se evalúan la presencia y abundancia de todas las especies vegetales existentes en un radio de xx m desde el centro de la parcela. La presencia de las especies se registra a través de un listado de taxones de Andalucía. Su abundancia se codifica según el criterio de Braun-Blanquet (búscalo en internet si no sabes lo que es). Cada muestreo es realizado por un equipo de personas cuyo número es variable. También es importante tener en cuenta que cada punto puede ser visitado en varias ocasiones. 

Ahora deberás hacer lo siguiente:
1. Construye un diagrama entidad-relación a partir de cada uno de los casos descritos más abajo. Identifica las entidades y los atributos importantes. Puedes poner los dos casos descritos en el mismo esquema o en dos difrentes. 
2. Traduce el o los diagramas entidad-relación en una o dos estructuras de bases de datos relacionales, con sus tablas y campos. 

## Evaluación
En la siguiente tabla podéis ver los criterios que se usarán para evaluar este ejercicio. Dicha rúbrica está basada en los pasos que hemos dado para construir la base de datos:

1. Identificación de entidades, atributos de la realidad que queremos modelar, así como las relaciones entre los mismos.
2. Traducción de los elementos anteriores a una estructura interpretable por un gestor de bases de datos relacionales: tablas, campos, relaciones.


<div style="page-break-after: always; break-after: page;"></div>

| Completitud de las entidades y sus atributos                 |             |                                                              |                                                              |                                                              |                                                              |                                                              |
| ------------------------------------------------------------ | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
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
|                                                              | 0.0         | 1.0                                                          | 2.0                                                          | 3.0                                                          | 4.0                                                          | 5.0                                                          |
|                                                              | No entrega. | Muy incompleta traducción de entidades/atributos a tablas/campos | Incompleta asignación de entidades/atributos a tablas/campos | Correcta traducción de entidades/atributos a tablas/campos   | Traducción completa                                          | Incorporas nuevas tablas y campos que mejoran la estructura. |
|                                                              |             |                                                              | Has traducido bien algunos elementos, pero faltan muchos.    | Están realizadas correctamente casi todas las asignaciones entidad/atributo a tabla/campo. | Todas las entidades y sus atributos han sido traducidos a tablas y a campos. |                                                              |





La evaluación de este ejercicio se realizará siguiendo las siguientes fases, que se basan en la idea de re-evaluación y análisis en grupo de resultados.



+ **Primera entrega**: Los alumnos entregan el ejercicio solicitado usando el conocimiento adquirido en las sesiones teóricas.
+ **Sesión de evaluación conjunta del ejercicio:** El profesor realiza el ejercicio junto con los alumnos. Definimos una estructura de datos que sea compatible con el enunciado del ejercicio. El siguiente diagrama muestra el resultado obtenido. También se puede descargar [aquí](https://github.com/aprendiendo-cosas/A_bbdd_ecoinf_ugr/raw/main/presentacion/ejercicio_bbdd.drawio.zip) en formato .drawio. Además, en el siguiente vídeo se muestra la sesión de trabajo conjunto.




<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&title=ejercicio_bbdd.drawio#R5V1bc6M6Ev41rpp9GBcSiMtjLpPZrZrZyqnUObvzlMK2xuYc2%2FICniTn16%2FEzUat2DgxknCeEoTA8KnV%2BrrV3Yzcm9Xz1zTeLL6zGV2OsDN7Hrm3I4yREzn8j2h5KVt8XDXM02RWddo1PCR%2F0%2FrKqnWbzGjW6pgztsyTTbtxytZrOs1bbXGasqd2t59s2f7VTTynoOFhGi9h63%2BSWb4oW0Mc7Nr%2FSZP5ov5l5EflmVVcd67eJFvEM%2Fa01%2BR%2BGbk3KWN5%2Bd%2Fq%2BYYuBXg1LuV1d6%2BcbR4speu8ywXZ7w7J%2F7i7%2Fvr7b97Cz77%2FFt3dfw6rZ8tf6hemM%2F7%2B1SFL8wWbs3W8%2FLJrvU7Zdj2j4q4OP9r1%2BcbYhjci3vgnzfOXajDjbc540yJfLauz8Mmrl8nYNp3SA49bS0Cczml%2BoF81OuJd9n6gwuUrZSuapy%2B8Q0qXcZ78ao91XInMvOm3Q5X%2FUwF7AsiRCZA5tunLf%2FnBZ2fsoLBu%2BSHuOPZJfXz7XP1EefSyf3RP04QjQNOqsf9x860at1oHXdrsIHahjC4TZc8ulLFRJeS09Y%2Bl6se1a8jcy5wY%2BNwoF5depWn8stdhw5J1nu3d%2BV408A41NQ0r7V4RU9eRBqy84W74mid7x4iWv%2FgrXm6rt7pny9GNO7q65YPEBE2m4jzlAMbTRJy5dte8ZcFWbF50jNY0BmLxtEhy%2BrCJi%2BF54kS845D%2BomlOnw8OQn0Wt9FC9dr4tCPFTZ%2FFHiH2nZ5mBwZY3rAJf59tGhfUf1Kilyrg4u%2BctxGKl8l8zf%2BfcoSEvrkWyCTcCriqTqyS2aycXzRL%2Fo4nxa3EDKvEjN%2BXXI%2FIrbgXn1JZObvOBL7rkhb4WIE9UmCP%2B8LeVWCftsDfZnzmXgLybbH3O0p9b8h7B6V%2BQUuxv0LTSxB7L2qBH5kGnwDwH7Z0WartbL2dseFDLmka5Cowd3Ri7gPM71i6ai2O5XK5HD74jtdW88S0ng8A%2BFf8rVPxom3eMnTkUVvNYwciH%2BkEHvsAU7upfyW5R7k%2Fssv34A7Nw9MVZxzZhfPQfDydcbbL04wgP7zfrvPGslxtaZanFGpsDRakHygNboMW5NCEknQVSscqocRG%2FFg71%2BPO2%2FhjtO9sVLsedYzP2T1g71POhsfnNNewhvFB3tlZyms%2BSNneiiRlVz5rdZk0zudwSEKT9o8kS%2FK4oPgF0S%2BXD%2FPLBVJZQ3rXCweAdUeni%2BE7WlDoS1h7EGui1f7BAOov2YZOE5o1kvmrElT9ohlIXkGloa5XNKGlLhRTvp1dgHBiSUeals0IYs3W8wsB22uLtkKyfZ1gR0YM9GwRb8SZZbL%2B612Uw%2B1qR4bo3IzjfZRQsc8QbwQrePjX15F7JUxJfvxY71SyNRimWq6%2FxRO6vOdymote7u2E5TlbKQQ%2FZxv1KKye5yK2cDyJs2Q63rDly1zc6Vr8d8NYOmsmxbUzFsrixhHzA98UDUG7AYkj0avdEBD5ErTXgKUGcMneTYuZKR6NC089dc8xMx3Jeg4Va47KM980nl1Iapnddw%2FnaTIRWmkkNIL%2Fv60IbrwGolKfAELTnrn9L%2BVYDgJQ7DGRQOdKHsKZN2WzxzidCNJjGVyeYnlQ%2BclJb2hB%2B6VCa5sZR8utQ4GtQQtupgm0il1j02B5xDawIKUWYGVix%2Ffxtf1e3agR7zhqqHa%2B64EtVM%2FIct%2FQMFx%2BB%2F2l0vb9oQVtCYHWz3KLW8GqdCMWkOOIKWlHb5BFkHVAP%2F7Q7C4sszsFD9Ea6hJBB8wFoCwJs4pD60UZBtLdJtPp47SO6YIkRj%2FJazK29qe8p5MTR2%2BJhpBs%2BN72k5pzZ9%2BviDo7D86ealBcempENZbcogGSEtKO9CfRkf6yb%2BrU%2Fu7h%2Fq7kaCQ6QsKjwC7Z9pDbku6x47lHJPzMyRrdxb6fXbqTxd4%2FUeyl%2FoQc7u85%2FqH%2BPYnlWxJDP5LKPXum4ptkz0VtlRUEh2WJSCGmUv%2BeZOkt%2Ba99qjhvOCru7OFlZxGz0DksZr4THOrfk5ipPacFl%2BbNn4Sjn5%2B%2Fcf8BxNEAqVaYHlr9zJHKc9pkkvhLYdhNOG7%2BXPz36WqbCZNObHdgB30WTImUB5h8JvzdyXg8NgGsSywDtvGGXJTpLCdCBYoIEa2mM3KgH%2Bjfg4fZk4KeiCIRQTPM0BE0fJiJfTBDT9DwYXYDYhvMkCMMH%2BZmX8wemCG5mAm%2FZrELRE04NX2vLYq%2BKvtAq1MTOZaZ2F5zbMgqQrWj47hZVEFn2CxqPOM1KZIrcB3pTyoS%2Flr%2FwIkO9e%2BpRgWxTC41uX66Sx%2BqN91Ni59kU0ZHxA%2BUPJEu6EmeHHXUSRURACxNo2Y6WCYU%2B7CarUkYhlIh53z6tk2y0gj%2FHqdlOnZcHouDEM23dBabgDFA1sEIAy2GT%2FzsM2Pq2PyLglnWsxbAfIkxMD4%2BrjQ0wwx9H4UZ04RnGTFlmtqzTU0i46ZMre4%2FGmWsK%2FQdN1jsYIyhFGbmRzoIIIK%2BrTrI0Tb%2BB%2BaWouCXXuKiqOiwFx3qfNoka879CtJH11NxYGgjJoysgw4aHsMnI6G0tWoBGYEWyvDJiAyzeTKCoTTfc2TEpBd5eUV5F9rkSA8cfhRGUsnLrkGoPQ6AohrahHOW%2BGOMgKsaAa2J16jOvLakYM9xRyHuJ0pMUUdE8gQ04Sb1PUou218dkaEVUsO48xj2E4J1vjE8ufB19MoP9WsFKFLKC2O6KDBjwo5GRKr66KnSQfQa0i7cON3mq8dnI%2FDI3kVFyI%2BqFkSP6EAKJNB5MYGOLycvmEcH8pM1W01SagQeOSbBPDzqxFRj9a1k7WMBQnCPpKyxZEQ7%2B1JgZ6AydFXVkPsDqB4hSYTMFaICGBn3uZAP6gn2OtsErh2xKyggUkz%2FkWw6RKR0ulCL87gG1ha1HcgxP8annIcBQj%2BVZQl1oBNZh44N%2BZXvUSzdi5Za9vE8D9oyTfyn8RKOkSSo5quLNuMHI30keIbmSuQ8RQI7gGDr9eUSuEPxMWhK2FmbOFbQFFD3LjySLQ1KKp9%2BgXfkAj88eEFfREhtvxpTodiR894Va32oV4OqqymptagGhJBnG0L1KgfX5Mdng3Zs1MXW12zIQlY9%2FOABPmfDtupSbOrp3dYmMDho%2BNEDSA4ZDRX0UjPOr9QVFbPfrrmv%2BsaiXj8fucTAIVC13gKZvMTIIeAn8xUF6zXjDHnR8HGWd5hUekMvzD4kV8NXG7tP0tRqQ5E5qxln6BKuw66MrmS%2BtKOHHMXMd1VFjPtbynzLSidiXZ4Ov%2BLvg%2FF0oEDijAgd81zIERqnX3HUOeLLBoOO4nPN4Nni60CBJ09thQtTrynvq7MqKk1omSJUoNWEDGqCS23%2FVHCZQCnE9snUK59T2AtzNmAgOl2kSVWDvEegLtJykWPazHuHfOj0Hj6lBrvkCJnn1NBELCv2mJz62JHKMSBVGgjWO%2FVr5bPvQjcKEgIgdf00VI8gYYDEh9hfDTqHgflnL179zhFTx1nZNv8tEO1L3LDAjkzZVUjrXZKCS6zVhyI5Fkb1rV3NQL8lre7syvo5yfd0NT%2F6sXdmp6nFQav%2B3CvF61z%2FiJY%2Fd%2FG6oHNoTW2K9p9RBj7rrPvz4gHcSSto5atpslpSU%2BRFRTkD9S4q0J406JkIZIRcVYkZzQipw58MogTkyAKUQmicXMCaKWfGWmAvK759O3wWCJIbkNvfpio%2FTJn4CvBuwRFfef7OZlT0%2BD8%3D"></iframe>



<iframe width="560" height="315" src="https://www.youtube.com/embed/v1Qc5kWc6Ac" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>












+ **Segunda ronda de evaluación:** Los alumnos rehacen el ejercicio teniendo en cuenta el nuevo conocimiento adquirido. 



**Ojo: este ejercicio no cuenta en la calificación de la asignatura. Se evalúa su desempeño, pero no cuenta para la nota**