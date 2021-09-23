# numeros_primos
Este programa verifica si un número es primo o no
n=int(input("ingresa el numero que deseas analizar (>0)"))

if n> 0:
    divisores=0
    i=2
    
    while i<n:
        if n%i==0:
            divisores+=1
        i+=1
    if divisores==0 and n>1:
        print("el numero es primo")
    else:
        print("el numero no es primo")
     
else:
    print("el numero debe ser mayor que cero")
