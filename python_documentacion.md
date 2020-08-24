# PYTHON
---
### Operadores Matematicos
**En la consola**

*Suma*
```py
5+5
```

*Resta*
```py
5-5
```

*Multiplicacion*
```py
5*5
```

*Division*
```py
25 / 5
```

*Division Euclidiana :Devuelve la parte Entera*
```py
21 // 5
```

*Recto de la Division:Sobra de la Division*
```py
21 % 5
```

*Potencia*
```py
5**5
```

**¿Que es una Variable?**
Es un identificador, en una variable puedo guardar objetos

----
### Los primitivos: Tipos de Datos

**se puede utilizar comillas  dobles(" ")  o simple(' ') y (+) se utiliza para concatenacion**
1-Numeros enteros
```py
a = 3
```

2-Numeros de punto flotante
```py
a = 3.4
```

3-Texto(Cadenas de caracteres)
```py
trabaja = 'false'
```

4-Booleanos(verdadero y falso)
```py
trabaja = true
```

---

### Convertir un dato a un tipo diferente:
***input(" ") para pedirle al usuario que introduzca datos***
```py
a = input("Escribe un número: ")
```

***int() con datos o variables dentro de parentesis para convertirlo en numero entero***
```py
a = 1  
b = 2 
c = a + b   
c = '12'
c = int(a) + int(b) = 3
```

***str() para convertir numeros tanto decimales como enteros a strings***
```py
b = 4
para llevarlo a string
str(b)='4'
```

***float() para convertir a flotantes***

------

### Operadores logicos y de comparacion

***Logicos:***
 "and"  para comparar si dos valores son verdaderos
 "or" para comparar si dos valores son falsos
 "not" para invertir el valor boliano 

```py
estudiante = true
trabaja = false 

estudiante and trabaja
false

estudiante or trabaja
true

not trabaja 
true
```
***Comparacion:***

" == " Compara dos valores y te dice sin son iguales. o no
" != " Compara dos valores  y te dice si son. diferentes o no.
" > " Compara si es mayor que otro valor.
" < " Compara si es menor que otro valor.
" >= " Igual o mayor que el valor a comparar.
" <= " Igual o menor que el valor a comparar.

------

***Ejemplo:***
```py
 //Tu primer programa conversosr de monedas//
pesos = input("Cuantos pesos Bolivianos tienes?: ")
pesos = float(pesos)
valor_dolar = 6.91
dolares = pesos / valor_dolar

//round: redondea a dos decimales// 
dolares = round(dolares, 2)
dolares = str(dolares)
print("Tienes $" + dolares + " dolares")
```

### Condicionales

```py
if (si)
else (si no)//si desea ejecujar otro codigo 
elif (si no)//se utiliza cuando utilizamos multiples condiciones
```

***Ejemplo***
```py
numero = int(input("Escribe un número: "))

if numero > 5:
    print("Es mayor a 5")
elif numero == 5:
    print("Es iguala a 5")
else:
    print("Es memor a 5")
```
---
### Funciones


```py
opcion = int(input("Elige una función (1,2,3): "))
if opcion == 1:
    print("Hola")
    print("Como estás")
    print("Elegiste la opción 1")
    print("Adios")
elif opcion == 2:
    print("Hola")
    print("Como estás")
    print("Elegiste la opción 1")
    print("Adios")
elif opcion == 3:
    print("Hola")
    print("Como estás")
    print("Elegiste la opción 1")
    print("Adios")
else
    print("Escribe la opcion correcta")
```

***Con las Funciones no se repite codigo***
```py
def conversacion(mensaje):
    print("Hola")
    print("Como estás")
    print(mensaje)
    print("Adios")
opcion = int(input("Elige una función (1,2,3): "))
if opcion == 1:
    conversacion("Elegiste la opción 1")
elif opcion == 2:
    conversacion("Elegiste la opción 2")
elif opcion == 3:
    conversacion("Elegiste la opción 3")
else
    print("Escribe la opcion correcta")
```

<!-- 
`para codigo`
*para cursiva*
**para negrita**
>cita -->