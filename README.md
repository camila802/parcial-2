# parcial-2
# un programa que en una lista no existen elementos repetidos
lista = input("ingrese una lista de elementos: ")
n = input ("ingrese el elemento que desea encontrar: ")
j = 0
for i in lista :
    if n == i:
        j += 1
print (f"el caracter {n} se encuentra {j} veces")

##un programa que determine si en una cadena se encuentra caracteres con dos o mas vocales, si la cadena existe imprimirla si no imprimir no existe
def obtener_vocales(frase):
    vocales = "a, e, i, o, u" 
    return set ([c for c in frase if c in vocales])

texto = "avena"
print (obtener_vocales(texto))
print (len(obtener_vocales(texto)))

### un programa que en dos listas determine que elementos tiene la primera que la segunda no tenga
lista1 = [1, 2, 3, 4, 5]
lista2 = [0, 1, 6, 7, 2]
for i in lista1:
    if i not in lista2:
        print(i)
#### un algoritmo que calcule el promedio de un arreglo de reales
def promedio_arreglo(A):
    s = 0 
    for x in A:
        s+= x
    return sum(A) /len(A)
print (promedio_arreglo([1, 4, 5, 6]))

#####determine la mediana de un arreglo de enteros(numero que queda en la mitad despues de ser ordenados)
def contador(B):
    s = 0
    for x in B:
        s+= x
    return sum(B) /len(B)
print (contador.sort(1, 3, 4, 4, 5))
