💰 Sistema Bancário em Python

Este é um projeto de sistema bancário simples desenvolvido em Python, com funcionalidades básicas como depósito, saque, visualização de extrato, criação de usuários e contas bancárias, e listagem de contas.

🧠 Funcionalidades

Criar usuários com CPF, nome, data de nascimento e endereço

Criar contas bancárias associadas aos usuários

Realizar depósitos

Realizar saques com limite de valor e quantidade por dia

Consultar extrato de movimentações

Listar todas as contas cadastradas

🚀 Como executar

Certifique-se de ter o Python 3.7+ instalado.

Clone este repositório ou copie o código para um arquivo sistema_bancario.py.

bash
Copiar
Editar
git clone https://github.com/seu-usuario/sistema-bancario-python.git
cd sistema-bancario-python
Execute o programa:

bash
Copiar
Editar
python sistema_bancario.py
📋 Exemplo de Menu
text
Copiar
Editar
[d] Depositar
[s] Sacar
[e] Extrato
[u] Novo Usuário
[cc] Criar Conta
[lc] Listar Contas
[q] Sair
🛠 Organização do Código
menu() – Exibe o menu principal

depositar() – Lida com a lógica de depósito

sacar() – Controla os saques com validações

exibir_extrato() – Mostra as transações realizadas

criar_usuario() – Cadastra novos usuários

filtrar_usuario() – Busca usuários por CPF

criar_conta() – Cria contas vinculadas a um CPF

listar_contas() – Lista todas as contas criadas

main() – Função principal que executa o programa

🧪 Exemplo de uso
text
Copiar
Editar
Informe o valor do depósito: 1000
Depósito realizado com sucesso!

Informe o valor do saque: 300
Saque realizado com sucesso!

================ EXTRATO ================
Depósito: R$ 1000.00
Saque: R$ 300.00

Saldo: R$ 700.00
========================================

📄 Licença
Este projeto é open-source e pode ser utilizado para fins educacionais ou pessoais. Nenhuma licença específica foi definida.
