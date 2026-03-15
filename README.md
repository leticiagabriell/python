


while True:
    print("[1] soma")
    print("[2] subtração")
    print("[3] multiplicação")
    print("[4] divisão")

    opicao = int(input("Digite sua opção: "))

    match opicao:
        case 1:
            n1 = int(input("Digite um número: "))
            n2 = int(input("Digite outro número: "))
            soma = n1 + n2
            print(f"Resultado: {soma}")

        case 2:
            n1 = int(input("Digite um número: "))
            n2 = int(input("Digite outro número: "))
            subtracao = n1 - n2
            print(f"Resultado: {subtracao}")

        case 3:
            n1 = int(input("Digite um número: "))
            n2 = int(input("Digite outro número: "))
            multiplicacao = n1 * n2
            print(f"Resultado: {multiplicacao}")

        case 4:
            n1 = int(input("Digite um número: "))
            n2 = int(input("Digite outro número: "))
            if n2 == 0:
                print("Não pode dividir por zero!")
            else:
                divisao = n1 / n2
                print(f"Resultado: {divisao}")

        case _:
            print("Opção inválida")
