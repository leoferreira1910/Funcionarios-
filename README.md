funcionarios = {}

while input("Quer inserir um funcionario? S-Sim, N-Não").upper() != "N":
    nome = input("Informe o nome do funcionário: ")
    funcao = input("Informe a função do funcionário: ")
    funcionarios.update({nome:funcao})

    print(funcionarios)
LookupError
