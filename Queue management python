ultimo = 10
fila = list(range(1, ultimo + 1))

sair = False
while not sair:
    print(f"Exitem {len(fila)} clientes na fila")
    print(f"Fila atual: {fila}")
    print("Digite F para adicionar um novo cliente no fim da fila")
    print("ou A para realizar o atendimento de um cliente")
    print("ou S para sair do programa")
    print("\n")

    operacao = input("F, A ou S: ")
    for i in range(len(operacao)):
        if operacao[i] == "A":
            if len(fila) > 0:
                atendido = fila.pop(0)
                print(f"Cliente {atendido} atendido")
            else:
                print("Não há ninguém para atender")
        elif operacao[i] == "F":
            ultimo += 1
            fila.append(ultimo)
        elif operacao[i] == "S":
            print("Saindo do programa...")
            sair = True
            break
        else:
            print("\n")
            print("Digite um valor válido (F, A ou S)")
