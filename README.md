#Ejercicio 3. Entrada: Numero. Salida:True si es positivo.

numero=int(input("Introduce un numero(+ o -):"))
print("¿Es positivo?")
esPositivo=(numero>0)
if esPositivo:
    print("Es positivo")
elif numero ==0: 
    print("Es 0")
else:
    print("Es negativo")


numero=int(input("Introduce tu nota"))
esAprobado=(numero >= 5)

if esAprobado:
  print ("Es aprobado")

else:
  print ("Es suspenso")


#Ejemplo
nota = int(input("Introduce tu nota:"))
print ("¿Que nota tiene?")
#Asumimos una nota válida: "if nota <=10 or nota >=9:"
if nota >10 or nota <0:
    print("No es una nota válida ")
elif nota <=10 and nota >=9:
    print("Sobresaliente")
elif nota < 9 and nota >=7:
    print ("Notable")
elif nota >=6: 
    print ("Bien")
elif nota >=5 :
    print ("Suficiente")
else:
    print ("Suspenso")
