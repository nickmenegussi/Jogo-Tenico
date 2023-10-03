# Jogo-Tenico


"""
while True:
    print("Digite uma nota de 1 a 10")
    nota = int(input("Digite uma nota: "))
    if nota >= 1 and nota <= 10:
        print("Parabens , voce digitou a nosa entre 1 a 10")
        break
    else:
        print(f"Erro , {nota} invalida ")
"""
"""print("="*15)
print("Tabuada".center(15))
print("="*15)
tabuda = int(input("Digite um valor que queira saber a tabuada: "))

for numero in range(1, 10 + 1):
    valor = tabuda*numero
    print(f"{numero} x {tabuda} = {valor}")
"""

numero = int(input("Digite quanto numeros que voce quer: "))
lista_numeros = []
soma_dos_numeros = 0

for valor in range(numero):
    num2 = int(input(f"Digite seu {valor} numero: "))
    lista_numeros.append(num2)
    
lista_numeros.sort()
lista_numeros.reverse()
print(lista_numeros)

for i in range(len(lista_numeros)):
    soma_dos_numeros += lista_numeros[i]
print(f"Menor valor: {lista_numeros[-1]}" )
print(f"Maior valor: {lista_numeros[0]}")
print(f"A soma dos números é {soma_dos_numeros}")
