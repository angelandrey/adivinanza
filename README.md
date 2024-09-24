# adivinanza
print(" ")
print("Angel Andrey Muñoz Centeno 3W")
print(" ")
import random

# Generar un número aleatorio entre 1 y 100
numero_secreto = random.randint(1, 100)

# Mensaje de bienvenida
print("¡Bienvenido al juego de adivinar el número!")
print("He elegido un número entre 1 y 100. ¡Intenta adivinarlo!")

# Inicializar intentos
intentos = 0

# Bucle para permitir al usuario adivinar
while True:
    # Solicitar al usuario que ingrese su adivinanza
    adivinanza = int(input("Introduce tu adivinanza: "))
    intentos += 1

    # Comparar la adivinanza con el número secreto
    if adivinanza < numero_secreto:
        print("Demasiado bajo. Intenta de nuevo.")
    elif adivinanza > numero_secreto:
        print("Demasiado alto. Intenta de nuevo.")
    else:
        print(f"¡Felicidades! Adivinaste el número {numero_secreto} en {intentos} intentos.")
        break
        ![image](https://github.com/user-attachments/assets/d129ca10-5977-4649-85f7-3e37d71ebb0d)
