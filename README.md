numero1 = int(input("Digite o numero 1:"))
operacao = input("Digite a operao:")
numero2 = int(input("Digite o numero 2:"))

if operacao == "+":
    resultado = numero1 + numero2
elif operacao == '-':
    resultado = numero1 - numero2
elif operacao == '/':
    resultado = numero1 / numero2
elif operacao == '*':
    resultado = numero1 * numero2
else:
    resultado = 'Operao invalida'

print(str(numero1) + ' ' + str(operacao) + ' ' + str(numero2) + ' = ' + str(resultado))

Este arquivo pode ser executado no Ubuntu Linux.
É uma estrutura de uma calculadora simples feita em Python, ao executar ela fara os calculos desejaveis.
