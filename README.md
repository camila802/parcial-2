# parcial-2
# un programa que en una lista no existen elementos repetidos
lista = input("ingrese una lista de elementos: ")
n = input ("ingrese el elemento que desea encontrar: ")
j = 0
for i in lista :
    if n == i:
        j += 1
print (f"el caracter {n} se encuentra {j} veces")

- para este ejercicio lo que hice fue crear una variable "lista" en la cual el usuario pudiera ingresar los elementos que quiera para despues pedir que encuentre el elemneto que desea para poder identificar cual elemento es el que se repite, al colocar n == i lo que le estoy pidiendo es encontrar un elemento en n que sea igual a un elemento de i para poder determinar si se repiten para despues colocar que el carcater de n esta x veces en j.
  

##un programa que determine si en una cadena se encuentra caracteres con dos o mas vocales, si la cadena existe imprimirla si no imprimir no existe
def obtener_vocales(frase):
    vocales = "a, e, i, o, u" 
    return set ([c for c in frase if c in vocales])

texto = "avena"
print (obtener_vocales(texto))
print (len(obtener_vocales(texto)))

- para este jercicio lo que hice fue definir las vocales para que el programa las pueda identificar despues al retornar lo que estoy haciendo es que le digo que al encontrar una de estas letras en una frase identifique si es una vocal y pueda imprimir el texto con esta funcion y ademas que vea la longitud del texto, lo que quiere decir toda la frase.

### un programa que en dos listas determine que elementos tiene la primera que la segunda no tenga
lista1 = [1, 2, 3, 4, 5]
lista2 = [0, 1, 6, 7, 2]
for i in lista1:
    if i not in lista2:
        print(i)
- En esta lo que hice fue determinar dos listas con datos diferentes para despues al utilizar if i not in lista2 busca los elementos que se encuentran en la lista 1 pero que la lista 2 no tiene.
#### un algoritmo que calcule el promedio de un arreglo de reales 
def promedio_arreglo(A):
    s = 0 
    for x in A:
        s+= x
    return sum(A) /len(A)
print (promedio_arreglo([1, 4, 5, 6]))
- para sacar el promedio realice una lectura de arreglo para poder colocar la formula en la que se realizan una suma de arreglos que le asigne y de esto sacar el promedio, sumandolos y dividiensolos 
#####determine la mediana de un arreglo de enteros(numero que queda en la mitad despues de ser ordenados)
def contador(B):
    s = 0
    for x in B:
        s+= x
    return sum(B) /len(B)
print (contador.sort(1, 3, 4, 4, 5))
