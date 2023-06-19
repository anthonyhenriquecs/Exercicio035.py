# Exercicio035.py
#Desenvolva um programa que leia o comprimento de três retas e diga ao usuário se elas podem ou não formar um triângulo.

n1 = float(input('Digite o 1° valor:'))
n2 = float(input('Digite o 2° valor:'))
n3 = float(input('Digite o 3° valor:'))
if n1 < n2 + n3 and n2 < n1 + n3 and n3 < n1 + n2:
    print('pode formar triangulo')
else:
    print('Não pode formar triangulo')
