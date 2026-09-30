# hola

#Determinar si un número es positivo negativo o "0"
def deter(a):
  if a > 0:
    return "su numero es positivo"
  elif a < 0:
    return "su número es negativo "
  else:
    return "su numero es 0"


numero = int(input("ingrese un numero: "))y
resp = deter(numero)
print(f"{resp}") 
