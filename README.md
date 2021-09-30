# 2021 Semestre 2
# Portafolio 2 Parte B

## Instrucciones Generales
- El archivo **debe** llamarse **Portafolio2B.py**
- **Debe** respetar el nombre de las funciones y el nombre de los parámetros que más adelante se describen
- Deben contruir las funciones con **Python**
- Debe utilizar la programación **Recursiva de COLA**
- Debe crear los comentarios de cada función tomando en cuenta **Nombre**, **Entrada**, **Salida** y **Restricciones**
- Fecha de entrega: **Miércoles 6 de Ovtubre a las 10pm**

##	Invertir elementos lista
Escriba un programa con sintaxis Python cuya función principal se llame **invertirLista(lista)**, que reciba como entrada una lista con números enteros denominado **lista** y que retorne la lista pero con los elementos invertidos 


```python
>>>invertirLista([5,8,45,96])
[96, 45, 8, 5]

>>> invertirLista([56, 85,8,45,96])
[96, 45, 8, 85, 56]

>>> invertirLista([])
"Error: La lista debe contener al menos 2 elementos"

>>> invertirLista([2,5,7,"ABC"])
"Error: La lista debe elementos tipo entero"
```

##	Elemento menor y mayor de la lista
Escriba un programa con sintaxis Python cuya función principal se llame **extremosLista(lista)**, que reciba como entrada una lista con números enteros denominado **lista** y que retorne la lista con 2 elementos donde ellos serán el número menor y mayor de la lista

```python
>>>extremosLista([18,5,8,45,96, 60])
[5,96]

>>> extremosLista([96, 96,96])
[96]

>>> extremosLista([])
"Error: La lista debe contener al menos 2 elementos"

>>> extremosLista([2,5,7,"ABC"])
"Error: La lista debe elementos tipo entero"
```

##	Eliminar elementos lista
Escriba un programa con sintaxis Python cuya función principal se llame **eliminarElementosLista(lista1, lista2)**, que reciba como entrada dos listas con números enteros denominado, donde **lista2** contiene los elementos a eliminar de **lista1** y que retorne la lista con los elementos eliminados

```python
>>>eliminarElementosLista([254, 25, 8], [25])
[254, 8]

>>> eliminarElementosLista([54, 25, 8], [25, 54])
[8]

>>> eliminarElementosLista([54, 25, 8], [21, 24])
[54,25,8]

>>> eliminarElementosLista([], [2,4])
"Error: La primera lista debe contener al menos 1 elemento"

>>> eliminarElementosLista([23,78,9], [])
"Error: La segunda lista debe contener al menos 1 elemento"

>>> extremosLista([2,5,7,"ABC"], [2,8])
"Error: La primera lista debe elementos tipo entero"

>>> extremosLista([2,5,7], [2,"8"])
"Error: La segunda lista debe elementos tipo entero"

```
