# Recursos online

| Libros                                                                                                                                                                             |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Introducción a las pruebas de sistemas de información - Federico Toledo](https://www.federico-toledo.com/libro-de-testing-introduccion-a-las-pruebas-de-sistemas-de-informacion/) |

| Videos     |
| :--------- |
| [asd](asd) |

# Teoría

## Responsabilidades de un Test Engineer

> Las principales responsabilidades de un ingeniero de pruebas consisten en probar un producto para asegurarse de que funciona correctamente y se comporta como está especificado. Para ello, diseña entornos de prueba, planes y casos de uso eficaces.

## Técnicas para el diseño de pruebas

| Técnica                                                    | definición                                                                                                                                                                                                                                                                                                                      |
| :--------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <font color="blue dark">Particiones de equivalencia</font> | Partición de equivalencia es la porción del dominio de una entrada o una salida para la cual se asume que el comportamiento de un componente o sistema, basado en la especificación, es el mismo. <br> <a href="https://youtu.be/aCCYwMiLoas">Técnica de Partición de Equivalencia \| ISTQB examinable</a>                      |
| <font color="blue dark">Valores límites</font>             | El análisis de valores limite es la técnica de diseño de pruebas de caja negra en la cual los casos de prueba son diseñados basándose en los valores límite.<br><a href="https://youtu.be/eFYFUUtTqdI">Técnica de Análisis de Valores Límites \| ISTQB examinable</a>                                                           |
| <font color="blue dark">Combinaciones por pares</font>     | Es una técnica de diseño de prueba de caja negra en los que los casos de prueba están diseñados para ejecutar todas las posibles combinaciones discretas de cada par de parámetros de entrada.<br><a href="https://youtu.be/UdaYBPNs9Qk">APRENDE a usar la Técnica de COMBINACIÓN por PARES 🤯 (PAIRWISE testing EXPLICADO)</a> |
| <font color="blue dark">Tablas de decisión</font>          | Es la técnica de diseño de casos de prueba de caja negra en la que los casos de prueba se diseñan para ejecutar las combinaciones de entradas y/o estímulos (causas) representadas en una tabla de decisión.<br><a href="https://youtu.be/Ir3rQFaIkrM">Técnica Tabla de Decisiones \| ISTQB examinable</a>                      |
| <font color="blue dark">Máquinas de estado</font>          | Es la técnica de diseño de pruebas de caja negra en la cual los casos de prueba son diseñados para ejecutar transiciones de estado válidas e inválidas.<br><a href="https://youtu.be/uxx2fwzgZBQ">Técnica Transición de Estado \| ISTQB examinable</a>                                                                          |
| <font color="blue dark">Casos de uso</font>                | Es la técnica de diseño de prueba de caja negra en la que los casos de prueba están diseñados para ejecutar escenarios de usuario. <br><a href="https://youtu.be/9CE3tOtej5s">Tecnica de casos de uso: Pruebas de caja negra \| ISTQB</a>                                                                                       |

## Test Case Template

| Test Case Field                                          | Description                                                                                                         |
| :------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| <font color="blue dark"> Test Suite ID</font>            | The ID of the test suite to which this test case belongs.                                                           |
| <font color="blue dark"> Test Case ID </font>            | The ID of the test case.                                                                                            |
| <font color="blue dark"> Test Case Summary</font>        | The summary / objective of the test case. belongs.                                                                  |
| <font color="blue dark"> Related Requirement </font>     | The ID of the requirement this test case relates/traces to.                                                         |
| <font color="blue dark"> Prerequisites </font>           | Any prerequisites or preconditions that must be fulfilled prior to executing the test. belongs.                     |
| <font color="blue dark"> Test Script / Procedure </font> | Step-by-step procedure to execute the test.                                                                         |
| <font color="blue dark"> Test Data</font>                | The test data, or links to the test data, that are to be used while conducting the test.                            |
| <font color="blue dark"> Expected Result </font>         | The expected result of the test.                                                                                    |
| <font color="blue dark"> Actual Result </font>           | The actual result of the test; to be filled after executing the test.                                               |
| <font color="blue dark"> Status </font>                  | Pass or Fail. Other statuses can be ‘Not Executed’ if testing is not performed and ‘Blocked’ if testing is blocked. |
| <font color="blue dark"> Remarks </font>                 | Any comments on the test case or test execution.                                                                    |
| <font color="blue dark"> Created By </font>              | The name of the author of the test case.                                                                            |
| <font color="blue dark"> Date of Creation </font>        | The date of creation of the test case.                                                                              |
| <font color="blue dark"> Executed By </font>             | The name of the person who executed the test.                                                                       |
| <font color="blue dark"> Date of Execution </font>       | The date of execution of the test.                                                                                  |
| <font color="blue dark"> Test Environment </font>        | The environment (Hardware/Software/Network) in which the test was executed.                                         |

## Test Case Example / Test Case Sample

| Test Case Field                                          | Description                                                                                                                                                                                                                    |
| :------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <font color="blue dark"> Test Suite ID</font>            | TS001                                                                                                                                                                                                                          |
| <font color="blue dark"> Test Case ID </font>            | TC001                                                                                                                                                                                                                          |
| <font color="blue dark"> Test Case Summary</font>        | To verify that clicking the Generate Coin button generates coins.                                                                                                                                                              |
| <font color="blue dark"> Related Requirement </font>     | RS001                                                                                                                                                                                                                          |
| <font color="blue dark"> Prerequisites </font>           | 1. User is authorized. <br> 2. Coin balance is available.                                                                                                                                                                      |
| <font color="blue dark"> Test Script / Procedure </font> | 1. Select the coin denomination in the Denomination field.<br> 2. Enter the number of coins in the Quantity field.<br> 3. Click Generate Coin.                                                                                 |
| <font color="blue dark"> Test Data</font>                | 1. Denominations: 0.05, 0.10, 0.25, 0.50, 1, 2, 5 <br> 2. Quantities: 0, 1, 5, 10, 20                                                                                                                                          |
| <font color="blue dark"> Expected Result </font>         | 1. Coin of the specified denomination should be produced if the specified Quantity is valid (1, 5)<br> 2. A message ‘Please enter a valid quantity between 1 and 10’ should be displayed if the specified quantity is invalid. |
| <font color="blue dark"> Actual Result </font>           | 1. If the specified quantity is valid, the result is as expected.<br> 2. If the specified quantity is invalid, nothing happens; the expected message is not displayed                                                          |
| <font color="blue dark"> Status </font>                  | Fail                                                                                                                                                                                                                           |
| <font color="blue dark"> Remarks </font>                 | This is a sample test case.                                                                                                                                                                                                    |
|                                                          |
| <font color="blue dark"> Created By </font>              | John Doe                                                                                                                                                                                                                       |
| <font color="blue dark"> Date of Creation </font>        | 01/14/2020                                                                                                                                                                                                                     |
| <font color="blue dark"> Executed By </font>             | Jane Roe                                                                                                                                                                                                                       |
| <font color="blue dark"> Date of Execution </font>       | 02/16/2020                                                                                                                                                                                                                     |
| <font color="blue dark"> Test Environment </font>        | OS: Windows Y <br> Browser: Chrome N                                                                                                                                                                                           |

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
