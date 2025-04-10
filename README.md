try:
    num1 = float(input("Digite a sua primeira nota: "))
    num2 = float(input("Digite a sua segunda nota: "))
    
    media = (num1 + num2) / 2

    print(f"\nSua média foi: {media:.2f}")

    if media >= 6:
        print("Parabéns, você foi aprovado!")
    elif media < 3:
        print("Você foi reprovado.")
    else:
        print("Você está de recuperação.️")
except ValueError:
    print("Erro: Digite um número válido para as notas.")
