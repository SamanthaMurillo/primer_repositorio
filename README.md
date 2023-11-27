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

- Restricciones: Se asume que al tener todos los datos de entrada definidos desde el problema 