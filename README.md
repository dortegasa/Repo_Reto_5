# Repo_Reto_5
Solución a los problemas planteados en el reto 5

Primer punto
```
a = int(input("Ingrese un número entero: "))

if a == 97 or a == 101 or a == 105 or a == 111 or a == 117:
    print("El número corresponde a una vocal minúscula.")
else:
    print("El número NO corresponde a una vocal minúscula.")
```

Segundo punto
```
a = input("Ingrese una a de longitud 1: ")
b = ord(a[0])

if b % 2 == 0:
    print("El código ASCII de la primera letra es par.")
else:
    print("El código ASCII de la primera letra es impar.")
```

Tercer punto
```
a = input("Ingrese un carácter: ")

if a >= '0' and a <= '9':
    print("El carácter ingresado es un dígito.")
else:
    print("El carácter ingresado NO es un dígito.")
```

Cuarto punto
```
a=float(input("Ingrese un numero: "))
if a<0:
    print("El numero "+str(a)+" es negativo")
elif a>0:
    print("El numero "+str(a)+" es positivo")
elif a==0:
    print("el numero "+str(a)+" es neutro para la suma")
else:
    print("Lo digitado no sigue los parametros")
```

Quinto punto
```
x = float(input("Ingrese la coordenada x del punto: "))
y = float(input("Ingrese la coordenada y del punto: "))
a = float(input("Ingrese la coordenada x del centro del círculo: "))
b = float(input("Ingrese la coordenada y del centro del círculo: "))
r = float(input("Ingrese el radio del círculo: "))
d = ((x - a)**2 + (y - b)**2)**0.5

if d < r:
    print("El punto está dentro del círculo.")
else:
    print("El punto NO está dentro del círculo.")

```

Sexto punto
```
a = float(input("Ingrese la longitud del primer lado: "))
b = float(input("Ingrese la longitud del segundo lado: "))
c = float(input("Ingrese la longitud del tercer lado: "))
if (a + b > c) and (a + c > b) and (b + c > a):
    print("Se puede construir un triángulo con estas longitudes.")
else:
    print("No se puede construir un triángulo con estas longitudes.")
```

El archivo del notebook esta adjuto al repositorio
