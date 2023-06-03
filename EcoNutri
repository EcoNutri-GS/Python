# Listas de dicas, receitas e orientações
dicas = [
    "Armazene corretamente os alimentos para prolongar sua vida útil.",
    "Planeje suas refeições e faça compras conscientes, evitando comprar em excesso.",
    "Aproveite as sobras de alimentos para criar novas receitas.",
    "Faça uma lista de compras antes de ir ao supermercado e siga-a para evitar compras impulsivas.",
    "Verifique regularmente a despensa e a geladeira para utilizar os alimentos antes que expirem."
]

receitas = [
    "Torta de Legumes com Sobras de Vegetais",
    "Arroz de Forno com Sobras de Arroz",
    "Bolinhos de Batata com Sobras de Purê",
    "Sopa de Legumes com Sobras de Vegetais",
    "Salada de Macarrão com Sobras de Frango Assado"
]

orientacoes_armazenamento = [
    "Armazene frutas e vegetais frescos na gaveta da geladeira para manter seu frescor.",
    "Evite armazenar alimentos perecíveis na porta da geladeira, pois a temperatura pode variar.",
    "Utilize recipientes herméticos para armazenar alimentos secos e evitar a entrada de umidade.",
    "Armazene carnes cruas separadamente de outros alimentos para evitar contaminação.",
    "Verifique sempre as datas de validade dos alimentos antes de armazená-los."
]

# Função para exibir o menu principal
def exibir_menu():
    print("")
    print("Menu:")
    print(" 1. Ver dicas e informações sobre redução de desperdício de alimentos")
    print(" 2. Ver receitas de aproveitamento de sobras")
    print(" 3. Configurar lembretes para consumo antes da validade")
    print(" 4. Doar alimentos excedentes")
    print(" 5. Orientações de armazenamento")
    print(" 6. Sair")

# Função para exibir as dicas e informações sobre redução de desperdício de alimentos
def exibir_dicas():
    print("")
    print("="*98)
    print("========================= Dicas para Reduzir o Desperdício de Alimentos ==========================")
    print("=" * 98)
    print("")
    for dica in dicas:
        print(f" - {dica}")

# Função para exibir as receitas de aproveitamento de sobras
def exibir_receitas():
    print("")
    print("=" * 98)
    print("============================== Receitas de Aproveitamento de Sobras ==============================")
    print("=" * 98)
    print("")
    for receita in receitas:
        print(f" - {receita}")

# Função para configurar lembretes para consumo antes da validade
def configurar_lembretes():
    print("")
    print("=" * 98)
    print("====================== Configurar Lembretes para Consumo Antes da Validade =======================")
    print("=" * 98)
    print("")
    produto = input("Digite o nome do produto: ")
    dia = input("Digite o dia de vencimento: ")
    while not dia.isnumeric():
        print("\nPor favor, informe apenas números.")
        dia = input("Digite o dia de vencimento: ")
    mes = input("Digite o mês de vencimento: ")
    while not mes.isnumeric():
        print("\nPor favor, informe apenas números.")
        mes = input("Digite o mês de vencimento: ")
    ano = input("Digite o ano de vencimento: ")
    while not ano.isnumeric():
        print("\nPor favor, informe apenas números.")
        ano = input("Digite o ano de vencimento: ")
    print(f"Lembrete configurado: Consumir {produto} até {dia}/{mes}/{ano}")

# Função para doar alimentos excedentes
def doar_alimentos():
    print("")
    print("=" * 98)
    print("=================================== Doar Alimentos Excedentes ====================================")
    print("=" * 98)
    print("")
    nome = input("Informe o seu nome: ")
    endereco = input("Informe o endereço de retirada dos alimentos: ")
    quantidade = input("Digite a quantidade de alimentos que deseja doar (números inteiros, em kg): ")
    while not quantidade.isnumeric():
        print("Por favor, informe apenas números.")
        quantidade = input("Digite a quantidade de alimentos que deseja doar (números inteiros, em kg): ")
    tipo_alimento = input("Digite o tipo de alimento que deseja doar: ")
    quantidade = int(quantidade)
    return print(f"\n{quantidade} kg de {tipo_alimento} serão retirados no endereço {endereco} para serem doados.\nSr(a) {nome}, nos da EcoNutri agradecemos pela sua contribuição!")

# Função para exibir as orientações de armazenamento
def exibir_orientacoes_armazenamento():
    print("")
    print("=" * 98)
    print("================================== Orientações de Armazenamento ==================================")
    print("=" * 98)
    print("")
    for orientacao in orientacoes_armazenamento:
        print(f" - {orientacao}")


# Apresentação
print("==================================== Bem-vindo(a) ao EcoNutri ====================================")
print("================== Com EcoNutri, a saúde e a sustentabilidade caminham juntas. ===================")
print("=" * 98)
# Loop principal do programa
while True:
    exibir_menu()
    escolha = input("Digite o número da opção desejada: ")

    if escolha == "1":
        exibir_dicas()
    elif escolha == "2":
        exibir_receitas()
    elif escolha == "3":
        configurar_lembretes()
    elif escolha == "4":
        doar_alimentos()
    elif escolha == "5":
        exibir_orientacoes_armazenamento()
    elif escolha == "6":
        print("\nNutrindo corpos e o planeta, desejamos uma jornada saudável e sustentável.\nAté logo, EcoNutri!")
        break
    else:
        print("\nOpção inválida! Por favor, escolha uma opção válida.")

    print("\nVocê deseja:\n 1. Menu\n 2. Sair")
    choice = input("Digite o número da opção desejada: ")
    if choice == "1":
        print("")
        print("=" * 98)
        continue
    else:
        print("\nNutrindo corpos e o planeta, desejamos uma jornada saudável e sustentável.\nAté logo, EcoNutri!")
        break
