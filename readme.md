# Sistema de Cadastro de Pessoas

Este é um sistema simples de cadastro de pessoas, implementado em Python, que permite ao usuário adicionar e listar cadastros. 
Os dados são armazenados em um arquivo JSON, permitindo que as informações sejam persistidas entre execuções do programa.

## Funcionalidades

- **Adicionar Novo Cadastro**: O usuário pode adicionar um novo cadastro informando nome, sexo, idade e email.
- **Listar Cadastros**: O sistema exibe uma lista com todos os cadastros feitos até o momento.
- **Salvar e Sair**: Quando o usuário decide sair, todos os dados são salvos no arquivo `dados_pessoais.json`.

## Como Usar

1. Clone este repositório para sua máquina.
2. Execute o script `sistema_cadastro.py` para iniciar o menu.
3. Escolha uma das opções no menu:
   - **1** para adicionar um novo cadastro.
   - **2** para listar os cadastros existentes.
   - **3** para salvar e sair do sistema.

### Exemplo de Execução


--- Menu de Opções---
1. adicionar novo cadastro
2. lista de cadastros.
3. Salvar e sair
Escolha uma opção: 1

--- Novo Cadastro ---
NOME.: João
SEXO.: Masculino
IDADE: 30
EMAIL: joao@gmail.com
Cadastro realizado com sucesso

--- Menu de Opções---
1. adicionar novo cadastro
2. lista de cadastros.
3. Salvar e sair
Escolha uma opção: 2

--- Lista de cadastros ---
1. Nome: João | Idade: 30 | Sexo: Masculino | Email: joao@gmail.com

#
