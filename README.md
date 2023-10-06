LUCA_1 = int(input("Ingrese valor 1: "))
LUCA_2 = int(input("Ingrese valor 2: "))

if LUCA_2 == 0:
    print("VOS SOS BOBO O TE HACES?")
    LUCA_2 = int(input("Ingrese valor 2: "))

Foca = LUCA_1 + LUCA_2
Foca_2 = LUCA_1 - LUCA_2
Foca_3 = LUCA_1 * LUCA_2
Foca_4 = LUCA_1 / LUCA_2

print(f"El resultado de la suma es: {Foca}")
print(f"El resultado de la resta: {Foca_2}")
print(f"El resultado de la Multiplicación es: {Foca_3}")
print(f"El resultado de la división es: {Foca_4}")
