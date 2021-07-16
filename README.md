# Informe_Laboratorio_4

Integrantes: Chachalo Mayerli, Mensias Adrian, Rosero Andres

## **PRÁCTICA No.4 TEOREMA DE SUPERPOSICIÓN**

## 1.  OBJETIVO DE LA PRÁCTICA

**Objetivo general** 

- Determinar de forma teórica y de forma experimental en el Tinkercad (simulador para armar circuitos eléctricos) los valores de tensión y de corriente en un circuito con más de una fuente de tensión con el uso del teorema de superposición teniendo en cuenta que este teorema se usa solamente en circuitos eléctricos lineales.

**Objetivos específicos**

- Comprobar los valores medidos y calculados y analizar la diferencia y el calculo del error que existe entre estos valores.

- Armar el circuito en Tinkercad (simulador para armar circuitos eléctricos) con la guia brindada para con esto realizar las respectivas mediciones.

## 2.  MARCO TEORICO

![image](https://user-images.githubusercontent.com/75383758/125713096-dcd89342-9c87-44a7-930e-84c5b8de4ceb.png)

## 3.  EXPLICACION DEL PROCEDIMIENTO 

3.1 **REQUISITOS PREVIOS**

Se requiere el análisis analítico del circuito mostrado en la figura 4.1., aplicando el
Teorema de Superposición. Obtenga los valores de VA e IX, respetando tanto la polaridad
del voltaje como el sentido de la corriente que se proporcionan y anote los resultados en
la tabla 4.1. y 4.2. según corresponda.

3.2 **NFORMACIÓN GENERAL**

Uno de los métodos que se aplica en el análisis de circuitos eléctricos que cuentan
con varias fuentes, es el Teorema de Superposición que establece que:

El voltaje o corriente a través de cualquier elemento del circuito puede obtenerse
sumando algebraicamente todos los voltajes o corrientes individuales generados por
cada fuente actuando por sí sola, con todas las demás fuentes igualadas a cero.

Las fuentes de voltaje igualadas a cero equivalen a un corto circuito, mientras que
las fuentes de corriente igualadas a cero equivalen a un circuito abierto.

 3.3 **MATERIAL Y EQUIPO REQUERIDO**

|**CANTIDAD**| **ELEMENTO**|
|:---: | :---: |
| 2 | Fuente de voltaje de C.D |
| 2 | Multimetros digitales |
| 1 | Resistor de 1 kΩ |
| 1 | Resistor de 2.2 kΩ |
| 1 | Resistor de 820 Ω |
| 1 | Resistor de 470 Ω |
| 1 | Protoboard |

3.4 **PROCEDIMIENTO PRÁCTICO**

3.4.1 Arme el circuito que se muestra en la figura 4.1.

![image](https://user-images.githubusercontent.com/85126275/125666869-90b25903-fa1c-40b2-ae7e-b20333a1acb4.png)

 **Circuito armado en Tinkercad**
 
![image](https://user-images.githubusercontent.com/85126275/125879796-bc0744c6-62db-4e0a-b1b7-b6bd1a9ec5e3.png)


3.4.2 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando
tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote
el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/85126275/125882812-288ed313-7f4f-4387-b63f-7f2adbb9e457.png)


3.4.3 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/85209614/125906320-fece4917-18a4-40f1-887b-aa9be18ebca5.png)




3.4.4 Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente
IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se
proporcionan. Anote el valor de las mediciones en la tabla 4.1 y 4.2 respectivamente.

![image](https://user-images.githubusercontent.com/85126275/125883285-837aeb5a-285f-4b9c-b3d8-72755c1cb5e2.png)

3.5 **PROCEDIMIENTO MATEMÁTICO**

Estableceremos dos casos de circuito el 1 y 2 esto con el fin de poder aplicar correctamente el teorema de superposición en cada caso una fuente estará cortocircuitada.

3.5.1 CASO 1

 En este caso tomaremos solamente la fuente de 20 voltios y cortocircuitaremos la fuente de 12 voltios

El circuito quedaría así quitando todo lo cortocircuitado.

![image](https://user-images.githubusercontent.com/85209614/125919021-5a6490fa-2ff6-4c3e-9cdc-975f59adeb75.png)

Ahora resolviendo el circuito por resistencias equivalente nos queda

![image](https://user-images.githubusercontent.com/85209614/125919208-e683de64-2cb8-4426-bf4e-8b07ac403c71.png)

![image](https://user-images.githubusercontent.com/85209614/125919236-2f4c5d99-1965-4768-8c27-d08537291a53.png)

Encontramos la intensidad total y voltaje VA del circuito

![image](https://user-images.githubusercontent.com/85209614/125919555-820a77b7-eb3f-4d5c-abae-1f983e3a7e0e.png)

3.5.2 CASO 2

En este caso es igual al anterior con la diferencia que ahora tomaremos solamente la fuente de 12 voltios y cortocircuitaremos la fuente de 20 voltios

El circuito quedaría así quitando todo lo cortocircuitado.

![image](https://user-images.githubusercontent.com/85209614/125921632-0b8e30a0-62d4-4aac-8178-140fedd6cc73.png)

Ahora resolviendo el circuito por resistencias equivalente nos queda

![image](https://user-images.githubusercontent.com/85209614/125921731-98e90130-d668-498d-8977-169e9e787bba.png)

![image](https://user-images.githubusercontent.com/85209614/125922044-1395424c-5145-430c-b682-47f8aeb24523.png)

Encontramos la intensidad X y voltaje VA del circuito

![image](https://user-images.githubusercontent.com/85209614/125922159-dd0cfa5e-5df4-46b4-b7d0-ada0f5834353.png)

3.5.3 TOTAL

Por ultimo según el teorema de superposición procedemos a sumar o restar los resistores o voltajes que se calcularon en el Caso A y B para dar con un valor total que represente al mismo resistor dentro del circuito original.

![image](https://user-images.githubusercontent.com/85209614/125922333-1ad7c367-cdb0-47a3-8ba5-2ff54d4c078b.png)

**TABLA 4.1**

Medicion de voltaje aplicando superposición 

|**Voltaje total (VA)**|           | **Voltaje (VA) cuando V2=0** |            | **Voltaje (VA) cuando V1=0** |           |
|        :--:          |   :---:   |            :---:             |   :---:    |            :---:             |   :---:   |
|        Calculado     |   Medido  |          Calculado           |   Medido   |            Calculado         |   Medido  |  
|                      |  0.952 V  |                              |   5.70 V   |                              |   6.53 V  | 
  


**TABLA 4.2**

Medicion de voltaje aplicando superposición 

|**Corriente total (Ix)**|           | **Corriente (Ix) cuando V2=0** |            | **Corriente (Ix) cuando V1=0** |           |
|        :--:            |   :---:   |            :---:               |   :---:    |            :---:               |   :---:   |
|        Calculado       |   Medido  |          Calculado             |   Medido   |            Calculado           |   Medido  |  
|                        |  0.025 A  |                                | 0.00695 A  |                                |  0.0255 A | 

3.4.5 Verifique el cumplimiento del Teorema de Superposición y compare los
resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus
conclusiones.

## 5.  VIDEO



## 6.  CONCLUCIONES 

- El Teorema de superposición permite evaluar los datos proporcionados por cada una de las fuentes en las diferentes resistencias de nuestro circuito eléctrico, para como paso final sumar estos datos y hallar los verdaderos valores proporcionados en el circuito.

- Al utilizar el teorema de superposición podemos realizar calculos en circutos con mas de una fuente de tensión conectada a este, puesto que estas fuentes pueden ser separadas y cuando se realiza la suma de las mismas notamos que existe una precisión casi exacta a cuando procedimos a la medición de dichos voltajes y corrientes.

## 7.  BIBLIOGRAFÍA

Teorema de superposici�n. Innovacionumh.es. (2021). Retrieved 15 July 2021, from https://innovacionumh.es/Proyectos/P_19/Tema_1/UMH_05.htm.

Log in. Lucid.app. (2021). Retrieved 15 July 2021, from https://lucid.app/documents#/dashboard.









