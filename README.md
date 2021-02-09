# FASORES - LABORATORIO 4

#### INTEGRANTES: EDISON CADENA - LIZBETH CHANGOLUISA

# 1.	OBJETIVOS

OBJETIVO GENERAL:

* Comprobar experimentalmente el Teorema de Superposición correspondiente con las dos fuentes y corriente seleccionada.

* La experiencia de este laboratorio consiste en hacer la configuración en un circuito eléctrico para comprobar experimentalmente el Teorema de Superposicion y aplicacion ya sea el caso de fuente de voltaje o fuente de corriente.

OBJETIVOS ESPECÍFICOS: 

* Afianzar experimentalmente las leyes de conservación de la energía eléctrica y la Conservación de la carga a traves de las mallas y Nodos.

* Verificar las voltajes medidios y corrientes medidios en donde se requiere segun el diagrama teórico.


# 2.	MARCO TEÓRICO

# TEOREMA DE SUPERPOSICION

* Resumen: 

Este método solamente se utiliza para circuitos lineales y para obtener voltajes e intensidades en un circuito.
El teorema de superposición establece que, el efecto dos o más fuentes de voltaje y/o corriente tienen sobre un punto cualquiera en un circuito lineal, es igual a la suma de cada uno de los efectos de cada fuente tomados por separado, sustituyendo todas las fuentes de voltaje restantes por un corto circuito y las fuentes de corriente por circuitos abiertos.
El teorema de superposición ayuda a encontrar:
•	Valores de tensión, en una posición de un circuito, que tiene más de una fuente de tensión y/o corriente.
•	Valores de corriente, en un circuito con más de una fuente de tensión y/o voltaje.

* Introducción:

¿Qué es el Teorema de Superposición?.

Se usa para la solución de redes con dos o más fuentes que no están en serie o en paralelo. La principal ventaja de este método es que la mayoría de las veces no requiere del uso de una técnica matemática, como la de determinantes, para encontrar los voltajes o las corrientes requeridas. En su lugar, cada fuente se analiza de manera independiente y la suma algebraica se encuentra para determinar una cualidad desconocida de la red.

¿Qué es el principio de Superposición?.

El principio de superposición establece que la respuesta (una corriente o tensión deseada) en un circuito lineal que tiene más de una fuente independiente se obtiene mediante la suma de las respuestas ocasionadas por las fuentes independientes separadas que actúan solas.

* Desarrollo:

Pasos a seguir
Para usar el teorema de superposición para el análisis de circuitos eléctricos, siga los pasos enlistados a continuación:

** Identificar las Fuentes independientes
Primero que nada tienes que identificar todas las fuentes independientes que hay en el circuito.

** Escoge una fuente y “apaga” las demás
Cada que escojas una fuente para analizar deberás “apagar” todas las demás. Reemplaza todas las fuentes de corriente con un circuito abierto y fuentes de voltaje con un circuito cerrado, exceptuando la fuente que estará considerando en los próximos pasos.

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/grafica%20marco%20teorico%20fuente%20voltaje%20fuente%20corrriente.jpg)

** Calcula el voltaje y la corriente
Encuentra la corriente en cada rama y el voltaje en cada nodo, sea cual sea la técnica que desee.

** Repita los dos pasos anteriores para cada fuente independiente
Repite el proceso anterior las veces que sea necesario. Dependiendo del número de fuentes independientes del circuito.

** Realiza la sumatoria
Finalmente, encuentre la suma algebraica de cada corriente de rama y voltaje de nodo de las corrientes y voltajes individuales anteriores.




# 3. EXPLICACIÓN

 
La aplicación del principio de superposición en el análisis de un circuito eléctricos comprende los siguientes pasos:

*	 Apagar todas las fuentes independientes excepto una. Calcular la salida (tensión o corriente) debido a la única fuente activa.

* 	Repetir el paso anterior para cada una de las fuentes independientes presentes en el circuito.

* 	La contribución total viene dada por la suma algebraica de las contribuciones de cada una de los voltajes  en las fuentes independientes.

* La contribución total viene dada por la resta algebraica de las contribuciones de cada una de las corrientes en las fuentes independientes.

# 4. LISTA DE COMPONENTES

Lista de Materiales y componetes necesarios para desarrollar el circuito expirementalmente y simularlo:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/Equipos%20y%20Materiales.jpg)


# 5.	DIAGRAMAS
 

Aplicando superposición sabemos que:
 
Donde Vo1 es la salida forzada o resultante de la influencia de la fuente de tensión V1 con la fuente de corriente apagada. Así mismo, Vo2 es la salida forzada o resultante de la influencia de la fuente de corriente I1 con la fuente de tensión apagada.

* Figura, Circuito Teórico para el análisis de mallas:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/Circuito%20Teorico.jpg)



* Circuito Experimental y simulado para el analisis de malla, medidos con multímetro respectivo a la corrriente de cada malla:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/circuito%20simulado.jpg)

*  Circuito Experimental con v1 cortocircuitado:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/circuito%20simulado%20v1%200.jpg)

*  Circuito Experimental con v2 cortocircuitado:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/circuito%20simulado%20v2%200.jpg)


# 6.	Procedimiento y funcionalidad

En este punto se debe explicar cómo funcionan la implementación del circuito o programa.

* Arme el circuito.

* Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando
tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote
el valor de las mediciones en la tabla.

* Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla.

* Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla.

# 7. APORTACIONES

Tabla de Registro de datos tomandos del Experimento:


![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/tabla%20de%20resultados%20excel.jpg)


Para poder econtrar los valores de la corriente para cada malla se aplicaron los sigueintes calulos:

* observamos las fuentes y aplicamos teoremas de superposicion:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/diagrama%20para%20v1%200.jpg)

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/diagrama%20para%20v2%200.jpg)

* Realizamos los calculos correspondientes aplicando ley de mallas y ley de ohm en cada circuito generado del teorema de superposicion: 

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/calculos.jpg)

* Obtenemos como resultados finales para el cricuito Total:

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/calculos%20finales.jpg)

Formula a aplicar para el calculo del ERROR: 

![](https://github.com/eddy90cg/lab-3-fce/blob/master/img/calculo%20error.jpg)


# 8.	CONCLUSIONES

* La superposición es una técnica muy útil para añadir a tu conjunto de herramientas que sirve para analizar circuitos. Usa la superposición cuando tengas un circuito con entradas múltiples o múltiples fuentes de poder.

* Se comprueba que podemos obtener voltaje y corriente aplicando los métodos en análisis de circuitos eléctricos que cuentan
con varias fuentes con el Teorema de Superposición.

* Obervamos que las fuentes de voltaje igualadas a cero equivalen a un corto circuito, mientras que
las fuentes de corriente igualadas a cero equivalen a un circuito abierto.

# 9.	BIBLIOGRAFÍA

Rodríguez, H. (19 de Octubre de 2017). lifeder. Obtenido de

     https://www.lifeder.com/leyes-kirchhoff/

Pérez, A. (12 de enero de 2015). Electrónica Completa. Obtenido de

     https://electronicacompleta.com/leyes-de-kirchhoff/

Recuperado de:

     https://dademuch.com/2019/11/08/principio-de-superposicion-analisis-de-circuitos-electricos/

# 10. ANEXOS

* Calculos a mano:

      https://github.com/eddy90cg/lab-3-fce/blob/master/Anexos/calculos%20a%20mano.pdf
   


