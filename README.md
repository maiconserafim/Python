# Python
Lista Python
exercicio 3

letra = input("Digite uma letra (F ou M): ")

if letra == "F":
    print("Feminino")
elif letra == "M":
    print("Masculino")
else:
    print("Sexo Inválido")

    exercicio 5
    
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))

media = (nota1 + nota2) / 2

if media == 10:
    print("Aprovado com Distinção")
elif media >= 7:
    print("Aprovado")
else:
    print("Reprovado")

    Exercicio 7
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))
num3 = float(input("Digite o terceiro número: "))

menor = min(num1, num2, num3)

numeros_ordenados = sorted([num1, num2, num3])
meio = numeros_ordenados[1]

print(f"O número do meio é: {meio}")
print(f"O menor número é: {menor}")

    exercicio  1
nota=float(input("informe um numero de 0 a 10: "))
while (nota>10) or (nota<0):
    print('numero invalido!')
    break
else:
    print('numero valido')

    exercicio 9
for i in range(1,51,2):
    print (i)

    Exercicio 9
n= -1
while n < 49:
    n += 2
    print(n)


