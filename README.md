# Soluciones a problemas de algoritmos propuestos

## Problema: Dada la edad de una persona saber si una persona votará en las elecciones

### Análisis
- Datos de entrada: Edad de una persona (x) expresada en años

- Restricciones: Edad mínima para votación (México) 18 años cumplidos.
> Nota: Dado que se trata de un ejemplo no se considera edad máxima, aunque para una implementación real podría considerarse, por ejemplo para evitar fraude electoral

- Resultado: Determinación de la posibilidad de voto para una persona conociendo el dato de su edad

### Construcción del algoritmo:

1. Leer el valor de la edad (x)
2. Si x < 18 informar al usuario del programa que la persona NO puede votar y terminar, en caso contrario pasar al paso 3
3. Informar al usuario del programa que la persona puede votar y terminar

----

### Prueba de escritorio

Dado el valor 15

1. x=15
2. ¿x < 18? Si, informar que la persona NO puede votar, terminar

Dado el valor 23

1. x=23
2. ¿x < 18? No, pasar a paso 3
3. Informar al usuario que la persona puede votar, terminar

## Problema: Dado el radio de un círculo, decir si el área es mayor a 20

### Análisis
- Datos de entrada: el radio de un círculo (r)

- Restricciones: r $\geq$ 0

- Resultado: Determinación de si el área es mayor a 20

### Construcción del algoritmo:

1. Leer el valor del radio (r)
2. Realizar la operación para determinar el área dada la fórmula para calcularala A = $\Pi$ * r^{2}
3. Si A < 20, informar que el área es menor a 20, terminar, en caso contrario pasar al paso 4
4. Informar que el área es mayor a 20, terminar

---

### Prueba de escritorio:
Dado r=5
1. Leer el valor de r
2. Realizar la operación A = 3.1416 * 5^{2} = 78.54
3. ¿A < 20? No, pasar al paso 4
4. Informar que el área es mayor a 20, terminar

## Problema: Juan gana $200 por hora, pedro gana $120 por hora, esta quincena juan trabajó 10 horas y pedro 15, ¿Juan recibió un sueldo mayor al de pedro?

### Análisis
- Datos de entrada: Salario Juan (SJ) = 200, Salario pedro (SP) = 120, Horas trabajadas Juan (HJ) = 10, horas trabajadas pedro (HP) = 15

- Restricciones: Se asume que al tener todos los datos de entrada definidos desde el problema no existe variación en los mismos, sin embago se pueden considerar restricciones si se varía cualquiera de los datos, según sentido común, por ejemplo: El salario de cualquier trabajador (SX) debe ser mayor que cero SX > 0, la hora trabajada de cualquier trabajador (HX) no puede ser negativa HX $\geq$ 0

- Resultado: Decir si Juan recibió un sueldo mayor que pedro

### Construcción del algoritmo

1. Leer SJ = 200, SP = 120, HJ = 10, HP = 15

2. Realizar la operación para determinar el salario total de cada uno:

STJ = SJ * HJ
STP = SP * HP

3. Si STJ > STP Indicar que Juan recibió un salario mayor que Pedro, terminar, de lo contrario pasar al paso 4

4. Indicar que Juan NO recibió un salario mayor que el de Pedro, terminar

--- 

### Prueba de escritorio:

1. SJ = 200, SP = 120, HJ = 10, HP = 15

2. STJ = 2000, STP = 1800

3. ¿STJ > STP? Si, Juan recibió un salario mayor que pedro

### Problema: Se vende un terreno en Tlalpan de 200 m^2 en $100,000 y uno en xochimilco de 180 m^2 en $95,000 ¿El metro cuadrado es más barato en xochimilco?

### Análisis

- Datos de entrada: Terreno tlalpan (TT) = 200 m^2, Terreno xocimilco (TX) = 180 m^2 Precio terreno Tlalpan (PT) = 100,000 Precio terreno Xocimilco (PX) = 95,000

- Restricciones: Tal como en el problema anterior la unica restricción es para el caso especifico de estos precios dados, por lo que se asume no existe restricción a la vista

- Resultado: Determinación de si en xocimilco el m^2 es más barato

### Construcción del algoritmo

1. Obtener los datos de entrada (TT) = 200 m^2,  (TX) = 180 m^2, Precio terreno Tlalpan (PT) = 100,000, Precio terreno Xocimilco (PX) = 95,000

2. Realizar la operación de obtención de precio por metro cuadrado en cada lugar

Precio por metro cuadrado Tlalpan (PMT) = 100,000 / 200.
Precio por metro cuadrado Xocimilco (PMX) = 95,000 / 180.

3. Si PMT > PMX Indicar al usuario que el precio por metro cuadrado es más barato en Xochimilco, terminar, en caso contrario pasar al paso 4

4. Indicar al usuario que el el precio por metro cuadrado es más caro en Xochimilco

---

### Prueba de escritorio

1. (TT) = 200 m^2,  (TX) = 180 m^2, (PT) = 100,000, (PX) = 95,000

2. Determinar el precio por metro cuadrado
PMT = 100,000 / 200 = 500.
PMX = 95,000 / 180 = 527.7.

3. ¿PMT > PMX? No, pasar al paso 4

4. Indicar al usuario que el precio por metro cuadrado es más caro en Xochimilco.


### Problema

Juan es estudiante de primer cuatrimestre de la carrera de TIC's y quiere conocer su promedio de calificaciones, las calificaciones que obtuvo fueron: 8,7,9,10,8.5 y 8.9

### Análisis

- Datos de entrada: Lista de calificaciones (8,7,9,10,8.5 y 8.9)

- Restricciones: Al ser un problema con valores establecidos se asume que no existe restricción más allá de la fórmula para calcular el promedio $\frac{x+x_1+x_2+...+x_n}{n}$

- Resultado: El promedio de las calificaciones de Juan

### Construccion del algoritmo

1. Leer los datos de entrada: 8,7,9,10,8.5 y 8.9

2. Sustituir en la formula para calcular el promedio dichos datos P = $\frac{8+7+9+10+8.5+8.9}{6}$ 

3. Informar al usuario del resultado P

---

### Prueba de escritorio

1. 8,7,9,10,8.5 y 8.9
2. P = $\frac{8+7+9+10+8.5+8.9}{6}$ = 8.5
3. Promedio = 8.5

### Problema:

Cristina y José Luis son estudiantes de primer cuatrimestre de la carrera de TIC's, se acaban de enterar que si obtienen un promedio minimo de 8.5 pueden soliticar una beca académica. Ellos llevan 6 materias de las cuales, cada uno conoces sus correspondientes calificaciones ¿Qué algoritmo deben utilizar para calcular su promedio y saber si pueden solicitar la beca

### Análisis:

- Datos de entrada: Las calificaciones de cada estudiante

- Restricciones: 6 números que indiquen las calificaciones, uno por materia, el promedio (P) debe ser $\geq$ 8.5 para ser acreedores a la beca

Resultado: El cálculo del promedio y la determinación de si son acreedores a la beca

### Construcción del algoritmo

1. Lectura de los datos de entrada: $x_1, x_2, \cdots , x_6$ 

2. Calcular el promedio: P = $\frac{x_1+x_2+ \cdots +x_6}{6}$

3. Si P $\geq$ 8.5 entonces indicar al usuario el promedio e indicar que es acreedor a una beca, terminar, de lo contrario pasar al paso 4

4. Indicar al usuario el promedio e indicar que NO es acreedor a una beca, terminar

--- 

Prueba de escritorio

Para calificaciones: 10,7,8,8,8,9

1.  10,7,8,8,8,9

2. P = 8.3

3. ¿8.3 $\geq$ 8.5? No, pasar al paso 4

4. Indicar al usuario P y que NO es acreedor a una beca

Para calificaciones: 10,9,8,10,10,8

1. 10,9,8,10,10,8

2. P = 9.1

3. ¿9.1 $\geq$ 8.5? Si, Indicar al usuario el promedio y que si es acreedor a una beca