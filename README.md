prueba
======
def Operaciones():

 #CALCULADORA - OPERACIONES
   
   Print
1) Suma
2) Resta
3) Multiplicacion
4) Division
5) Exponente


def Calculadora():

    Menu()

opc = int (input ("Seleccione la operaciÃ³n a realizar\n"))
   
     while (opc > 0 and opc < 6):

x = int (input ("Ingrese primer valor\n"))
y = int (input ("Ingrese segundo valor\n"))
    if (opc==1):
            print "El resultado es:", x+y
            opc = int(input("Seleccione la operaciÃ³n a realizar\n"))
        elif(opc==2):
            print "El resultado es: ",x-y
            opc = int(input("Seleccione la operaciÃ³n a realizar\n"))
        elif(opc==3):
            print "El resultado es: ",x*y
            opc = int(input("Seleccione la operaciÃ³n a realizar\n"))
        elif(opc==4):
            print "El resultado es: ", x/y
            opc = int(input("Seleccione la operaciÃ³n a realizar\n"))
        elif(opc==5):
            print "El resultado es: ", x**y
            opc = int(input("Seleccione la operaciÃ³n a realizar\n"))
