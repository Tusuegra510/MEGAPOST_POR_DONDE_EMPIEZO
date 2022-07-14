# Recursos online

| Libros                                                                                                                                                                             |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Introducción a las pruebas de sistemas de información - Federico Toledo](https://www.federico-toledo.com/libro-de-testing-introduccion-a-las-pruebas-de-sistemas-de-informacion/) |

| Videos     |
| :--------- |
| [asd](asd) |

# Teoría

#### Responsabilidades de un Test Engineer

> Las principales responsabilidades de un ingeniero de pruebas consisten en probar un producto para asegurarse de que funciona correctamente y se comporta como está especificado. Para ello, diseña entornos de prueba, planes y casos de uso eficaces.

## Técnicas para el diseño de pruebas

| Técnica                                                | definición                                                                                                                                                                                                                                                                                                                      |
| :----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <font color="green">Particiones de equivalencia</font> | Partición de equivalencia es la porción del dominio de una entrada o una salida para la cual se asume que el comportamiento de un componente o sistema, basado en la especificación, es el mismo. <br> <a href="https://youtu.be/aCCYwMiLoas">Técnica de Partición de Equivalencia \| ISTQB examinable</a>                      |
| <font color="green">Valores límites</font>             | El análisis de valores limite es la técnica de diseño de pruebas de caja negra en la cual los casos de prueba son diseñados basándose en los valores límite.<br><a href="https://youtu.be/eFYFUUtTqdI">Técnica de Análisis de Valores Límites \| ISTQB examinable</a>                                                           |
| <font color="green">Combinaciones por pares</font>     | Es una técnica de diseño de prueba de caja negra en los que los casos de prueba están diseñados para ejecutar todas las posibles combinaciones discretas de cada par de parámetros de entrada.<br><a href="https://youtu.be/UdaYBPNs9Qk">APRENDE a usar la Técnica de COMBINACIÓN por PARES 🤯 (PAIRWISE testing EXPLICADO)</a> |
| <font color="green">Tablas de decisión</font>          | Es la técnica de diseño de casos de prueba de caja negra en la que los casos de prueba se diseñan para ejecutar las combinaciones de entradas y/o estímulos (causas) representadas en una tabla de decisión.<br><a href="https://youtu.be/Ir3rQFaIkrM">Técnica Tabla de Decisiones \| ISTQB examinable</a>                      |
| <font color="green">Máquinas de estado</font>          | Es la técnica de diseño de pruebas de caja negra en la cual los casos de prueba son diseñados para ejecutar transiciones de estado válidas e inválidas.<br><a href="https://youtu.be/uxx2fwzgZBQ">Técnica Transición de Estado \| ISTQB examinable</a>                                                                          |
| <font color="green">Casos de uso</font>                | Es la técnica de diseño de prueba de caja negra en la que los casos de prueba están diseñados para ejecutar escenarios de usuario. <br><a href="https://youtu.be/9CE3tOtej5s">Tecnica de casos de uso: Pruebas de caja negra \| ISTQB</a>                                                                                       |

# Preguntas de entrevistas

| ¿Qué es software testing? |
| :------------------------ |

> Según Cem Kaner es una investigación técnica realizada para proveer información a los stakeholders sobre la calidad del producto o servicio bajo pruebas.
> <br><br>
> Según Glenford Myers, software testing es un proceso diseñado para asegurar que el código hace lo que se supone que debe hacer y no hace lo que se supone que no debe.
> <br><br>
> Según el autor, se trata de un proceso en el que se ejecuta un programa con el objetivo de encontrar errores.
> <br><br>
> Lo más importante: aportar calidad al software que se está verificando. ¿Cómo? Detectando posibles incidencias de diversa índole que pueda tener cuando esté en uso.

| ¿Cuáles son las fases en el ciclo de pruebas de software? |
| :-------------------------------------------------------- |

> - Análisis de requisitos
> - Planeación de pruebas
> - Diseño de casos
> - Configuración de ambiente
> - Ejecución de pruebas
> - Cierre

| ¿Porqué es importante el análisis de requisitos? |
| :----------------------------------------------- |

> Se requiere entender los requerimientos, historias de usuario, criterios de aceptación para poder definir los casos de prueba y posteriormente validar que el sistema cumpla con los resultados esperados.

| ¿Qué información básica debe tener un buen caso de prueba? |
| :--------------------------------------------------------- |

> - Tipo de prueba
> - Descripción del caso
> - Pasos (flujo)
> - Estado
> - Resultado esperado
> - Resultado obtenido

| ¿Qué información básica debe tener un buen reporte de bug? |
| :--------------------------------------------------------- |

> - Tipo del bug
> - Resumen del bug
> - Pasos de reproducción
> - Resultado esperado
> - Resultado obtenido
> - Ambiente / browser / SO
> - Screenshot / stack trace / logs

| ¿Cuál es el ciclo de vida de un bug? |
| :----------------------------------- |

> - Nuevo
> - Asignado
> - Activo (Rechazado / Reabierto)
> - Verificado
> - Cerrado

| ¿Qué tipos de pruebas hay? |
| :------------------------- |

> ### Pruebas funcionales
>
> - unit test
> - smoke test
> - integración
> - regresión
> - aceptación
>
> ### Pruebas no funcionales
>
> - stress
> - carga
> - rendimiento
> - seguridad

| ¿Cuándo se debería automatizar un caso de prueba? |
| :------------------------------------------------ |

> - Cuando la prueba se corre de manera frecuente (smoke test)
> - Cuando hay flujos extensos que consumen mucho tiempo
> - Cuando se requiere correr la misma prueba en múltiples exploradores
> - Pruebas de regresión repetitivas
