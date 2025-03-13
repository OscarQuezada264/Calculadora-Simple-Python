# Calculadora-Simple-Python
Este código implementa una calculadora simple en Python que puede realizar operaciones básicas como suma, resta, multiplicación y división,es un buen ejemplo para principiantes que quieren practicar funciones y manejo de errores.
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: División por cero"
    return a / b

# Ejemplo de uso
print("Suma:", sumar(5, 3))
print("Resta:", restar(5, 3))
print("Multiplicación:", multiplicar(5, 3))
print("División:", dividir(5, 0))
