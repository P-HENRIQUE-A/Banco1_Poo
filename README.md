💰 Sistema Bancário em Python 🐍
Um projeto de sistema bancário orientado a objetos (OOP) desenvolvido em Python. Permite a criação de contas correntes e contas poupança, registro de transações (depósitos e saques), e geração de extratos. O objetivo principal é aplicar conceitos de programação orientada a objetos como herança, encapsulamento, polimorfismo e composição.





🛠️ Tecnologias utilizadas
 Python 3.10+

 Orientação a Objetos (POO)

 Módulo abc para classes abstratas

 Tipagem e boas práticas

 Interface de terminal (CLI)



📁 Estrutura do Projeto
.desafio1_poo.py
├── banco1_poo.py              # Arquivo principal com toda a lógica do sistema
└── README.md            # Este arquivo



👤 Funcionalidades
✅ Cadastro de clientes (Pessoa Física)
✅ Criação de contas Corrente ou Poupança
✅ Depósitos e saques com regras de negócio distintas
✅ Geração de extrato completo por cliente
✅ Histórico de transações diárias
✅ Limite de saques para conta corrente
✅ Iterador personalizado para exibir lista de contas





🧠 Conceitos aplicados
📦 Encapsulamento: Atributos protegidos com _ para controle interno
🔁 Polimorfismo: sacar() se comporta diferente em ContaCorrente e ContaPoupanca
🏗️ Herança: Cliente → PessoaFisica, Conta → ContaCorrente / ContaPoupanca
⚙️ Composição: Classe Cliente contém contas, Conta possui Historico





▶️ Como executar
Certifique-se de ter o Python 3.10 ou superior instalado.
Clone o repositório:
bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio





🖥️ Demonstração (CLI)
=============== MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta (corrente ou poupança)
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=> 





🚀 Melhorias futuras
Integração com interface gráfica (Tkinter ou Web)

Armazenamento em arquivo ou banco de dados

Suporte para contas jurídicas

Autenticação de usuários com senha

👨‍💻 Autor

Feito com 👨‍💻 por Paulo Henrique de Andrade
