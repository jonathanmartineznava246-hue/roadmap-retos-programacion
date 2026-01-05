# ===============================
# OPERADORES EN PYTHON
# ===============================

print("OPERADORES ARITMÉTICOS")
a = 10
b = 3
print(a + b)    # suma
print(a - b)    # resta
print(a * b)    # multiplicación
print(a / b)    # división
print(a % b)    # residuo

print("\nOPERADORES DE COMPARACIÓN")
print(a > b)
print(a == b)
print(a != b)

print("\nOPERADORES LÓGICOS")
print(a > 5 and b < 5)
print(a > 5 or b > 5)
print(not a < 5)

print("\nOPERADORES DE ASIGNACIÓN")
c = 5
c += 2
print(c)

print("\nOPERADORES DE PERTENENCIA")
lista = [1, 2, 3, 4]
print(3 in lista)
print(5 not in lista)

print("\nOPERADORES DE IDENTIDAD")
x = lista
y = [1, 2, 3, 4]
print(x is lista)
print(x is y)

print("\nOPERADORES A NIVEL DE BITS")
d = 6
e = 3
print(d & e)
print(d | e)


# ===============================
# ESTRUCTURAS DE CONTROL
# ===============================

print("\nCONDICIONAL IF")
edad = 18
if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")

print("\nBUCLE FOR")
for i in range(3):
    print(i)

print("\nBUCLE WHILE")
contador = 0
while contador < 3:
    print(contador)
    contador += 1

print("\nEXCEPCIONES")
try:
    numero = 10 / 0
except:
    print("Error: división entre cero")


# ===============================
# DIFICULTAD EXTRA
# ===============================

print("\nNUMEROS DEL 10 AL 55")
for num in range(10, 56):
    if num % 2 == 0 and num != 16 and num % 3 != 0:
        print(num)
