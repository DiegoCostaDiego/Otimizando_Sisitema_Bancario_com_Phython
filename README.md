# Otimizando_Sisitema_Bancario_com_Phython
Repositório do Desafio de Projeto - Otimizando o Sistema Bancário
Potência Tech powered by iFood | Ciências de Dados com Python
# Sistema Bancário Simples em Python

Este é um código simples de simulação de operações bancárias implementado em Python. O programa oferece um menu para o usuário realizar várias operações, incluindo:

1. Depositar
2. Sacar
3. Extrato
4. Nova Conta
5. Listar Contas
6. Novo Usuário
0. Sair

## Como usar

Após iniciar o script Python, você verá um menu de opções. Para escolher uma opção, basta digitar o número correspondente e pressionar Enter.

### Depósito

Ao escolher a opção "Depositar", o sistema solicitará que você insira o valor a ser depositado. O valor será adicionado ao saldo da conta. Se você inserir um valor negativo ou igual a zero, o sistema retornará uma mensagem de erro.

### Saque

Ao escolher a opção "Sacar", o sistema solicitará que você insira o valor a ser sacado. O valor será subtraído do saldo da conta. Se você inserir um valor maior do que o saldo da conta, um valor negativo, ou se você exceder o limite de saques permitidos(3), o sistema retornará uma mensagem de erro.

### Extrato

A opção "Extrato" exibirá todas as transações realizadas, bem como o saldo atual da conta.

### Nova Conta

A opção "Nova Conta" permitirá que você crie uma nova conta bancária. Será necessário fornecer o CPF do usuário titular da conta. Se o CPF fornecido já estiver associado a um usuário existente, o sistema retornará uma mensagem de erro.

### Listar Contas

A opção "Listar Contas" irá listar todas as contas existentes, com detalhes como a agência, o número da conta e o titular.

### Novo Usuário

A opção "Novo Usuário" permitirá que você crie um novo usuário no sistema bancário, fornecendo detalhes como o nome completo, CPF, data de nascimento e endereço. Se o CPF fornecido já estiver associado a um usuário existente, o sistema retornará uma mensagem de erro.

## Notas

- Este código é uma simulação simples e não deve ser usado para operações bancárias reais.
- O sistema não mantém os dados após o término da execução. Todas as transações e dados do usuário são perdidos ao finalizar o programa.
- Este é um código de exemplo, criado para demonstrar as funcionalidades básicas de um sistema bancário.

