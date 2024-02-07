# Encuentra_el_cuadrante.py
.
#Solicitar al usuario que ingrese las coordenadas X y Y
x = float(input("Ingrese la coordenada X: "))
y = float(input("Ingrese la coordenada Y: "))

#Verificar que ninguna coordenada sea 0
if x == 0 or y == 0:
    print("Una de las coordenas es cero. Poe favor, ingrese coordenadas diferentes de cero. ")
else:

#Determinar en que cuadrante se encuentra el punto
 if x > 0 and y > 0:
    print("El punto se encuentra en el cuadrante I ")
 elif x < 0 and y < 0:
    print("El punto se encuentra en el cuadrante II ")
 elif x < 0 and y < 0:
    print("El punto se encuentra en el cuadrante III ")
 else:
    print("El punto se encuentra en el cuadrante IV ")
