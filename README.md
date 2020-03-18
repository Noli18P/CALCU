# CALCU
Este es el primer programa que realice 100% SOLO. CALCU te pregunta por la operación que realizará.

#CALCU programa que te ayuda y te habla con tus operaciones.

import time

#Introduccion al usuario
def introduccion():
    print('Hola humano, yo soy CALCU y te ayudaré con tus operaciones matematicas')
    time.sleep(1)
    print('Primero tienes que escojer la operacion que realizare')
    time.sleep(1)
    print('1 = SUMA, 2 = RESTA, 3 = MULTI, 4 = DIVISION.')
    time.sleep(1)

introduccion()

#Eleccion del tipo de operacion
def elegirSuma():
    elegirSuma = input()
    if elegirSuma == '1':
        n1 = 0
        n2 = 0
        print('Ok...sumemos')
        time.sleep(1)
        print('Introduce un numero:')
        n1 = input()
        print('Introduce otro numero:')
        n2 = input()
        print('Realizando calculos...')
        time.sleep(1)
        print(int(n2) + int(n1))

elegirSuma()

def elegirResta():
    elegirResta = input()
    if elegirResta == '2':
        m1 = 0
        m2 = 0
        print('Ok...restemos')
        time.sleep(1)
        print('Introduce un numero:')
        m1 = input()
        print('Introduce otro numero:')
        m2 = input()
        print('Realizando calculos...')
        time.sleep(1)
        print(int(m1) - int(m2))

elegirResta()

def elegirMulti():
    elegirMulti = input()
    if elegirMulti == '3':
        a1 = 0
        a2 = 0
        print('Ok...multipliquemos')
        time.sleep(1)
        print('Introduce un numero:')
        a1 = input()
        print('Introduce otro numero:')
        a2 = input()
        print('Realizando calculos...')
        time.sleep(1)
        print(int(a1) * int(a2))

elegirMulti()

def elegirDiv():
    elegirDiv = input()
    if elegirDiv == '4':
        b1 = 0
        b2 = 0
        print('Ok...dividamos')
        time.sleep(1)
        print('Introduce un numero:')
        b1 = input()
        print('Introduce otro numero:')
        b2 = input()
        print('Realizando calculos...')
        time.sleep(1)
        print(int(b1) / int(b2))

elegirDiv()

#Aqui se pregunta al usuario si quiere volver a empezar
calcularDeNuevo = 'si'
while calcularDeNuevo == 'si' or calcularDeNuevo == 's':

    calcularDeNuevo = input()
    print('¿Quieres que haga otra operacion?) (si o no)')
    introduccion()
        
    
