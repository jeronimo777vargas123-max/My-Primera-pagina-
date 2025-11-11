Pensamiento algorítmico 

UNIDAD 1 

Pensamiento Algorítmico-Variables y Estructura de Datos:

en esta primera unidad se exploró los fundamentos del pensamiento algorítmico y el cómo se conectan con el Hardware, 
el Software y los lenguajes de programación en especial el programa Python 

También vimos como los computadores almacenan y el cómo manipulan la información. 

Que es un programa: 
es una serie de instrucciones que el computador puede entender y ejecutar para resolver problemas o realizar tareas. 

Hardware:
Es la parte física del computador (procesador, memoria, almacenamiento y dispositivos de entradas).

Software:
son los programas el cual le indica al computador que hacer.

Lenguaje de Programación: 
Forma en que las personas le dan instrucciones a la computadora.

Variables y tipos de datos: 
Una variable almacena información la cual puede cambiar. 

Operadores:
Permite hacer operaciones matemáticas, comparaciones y lógicas 

Funciones:
Son bloque de códigos reutilizables que realizan una tarea específica. Puede recibir valores y devolver resultados.

Código Python:

 PENSAMIENTO ALGORÍTMICO – UNIDAD 1
 

nombre = "Jerónimo"       # Tipo de dato: string (texto)
edad = 19              # Tipo de dato: entero (int)
altura = 1.60          # Tipo de dato: flotante (float)
es_estudiante = True    # Tipo de dato: booleano (True/False)

suma = edad + 8         # suma
resta = edad - 4        # resta
multiplicacion = edad * 3
division = edad / 3


mayor_edad = edad >= 18   # devuelve True o False


puede_entrar = mayor_edad and es_estudiante  # True si ambas condiciones son verdaderas


def saludar(nombre_usuario):
    """
    Esta función recibe un valor (nombre_usuario) y lo usa para generar un saludo.
    """
    print("Hola", nombre_usuario, "¡Bienvenido al mundo de Python!")

def calcular_promedio(n1, n2, n3):
    """
    Esta función recibe 3 números, calcula el promedio y lo devuelve.
    """
    promedio = (n1 + n2 + n3) / 3
    return promedio


saludar(nombre)  # Llamamos la función saludar

promedio_notas = calcular_promedio(4.5, 3.8, 5.0)
print("El promedio de tus notas es:", promedio_notas)


if mayor_edad:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")

print("¿Puedes entrar al laboratorio?:", puede_entrar)


print("\nHARDWARE es la parte física del computador.")
print("SOFTWARE es el conjunto de programas que ejecuta el hardware.")
print("Un LENGUAJE DE PROGRAMACIÓN permite dar instrucciones a la computadora.")
✅ Qué muestra este código:

Variables y diferentes tipos de datos

Operaciones matemáticas, comparaciones y lógicas

Funciones con parámetros y retorno

Estructuras básicas de un programa

Relación con los conce


Reflexión:
En la primera unidad aprendí como los programas se construyen a partir de instrucciones simples y lógicas y como el pensamiento algorítmico nos ayuda a resolver problemas paso a paso. 
Me pareció interesante como algo tan simple como una variable puede ser la base para construir proyectos mucho más complejos.




