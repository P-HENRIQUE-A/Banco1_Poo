# 💰 Sistema Bancário em Python 🐍

Um projeto de **sistema bancário orientado a objetos (OOP)** desenvolvido em **Python**.  

Este sistema permite:
- Criação de **contas correntes** e **contas poupança**
- **Registro de transações** (depósitos e saques)
- **Geração de extratos**
- Aplicação de conceitos como **herança**, **encapsulamento**, **polimorfismo** e **composição**

---

## 🛠️ Tecnologias utilizadas
- **Python 3.10+**
- Programação Orientada a Objetos (POO)
- Módulo `abc` (classes abstratas)
- Tipagem estática e boas práticas
- Interface de terminal (CLI)

---

## 📁 Estrutura do projeto
.

├── desafio1_poo.py # Arquivo de desafio / inicialização

├── banco1_poo.py # Lógica principal do sistema

└── README.md # Documentação do projeto

---

## 👤 Funcionalidades
✅ Cadastro de clientes (Pessoa Física)  
✅ Criação de contas Corrente e Poupança  
✅ Depósitos e saques com regras específicas  
✅ Geração de extrato completo por cliente  
✅ Histórico de transações diárias  
✅ Limite de saques para Conta Corrente  
✅ Iterador para listar contas  

---

## 🧠 Conceitos aplicados
- **Encapsulamento:** atributos protegidos (`_`) para uso interno  
- **Polimorfismo:** `sacar()` tem comportamento diferente em `ContaCorrente` e `ContaPoupanca`  
- **Herança:** `Cliente` → `PessoaFisica`; `Conta` → `ContaCorrente` / `ContaPoupanca`  
- **Composição:** `Cliente` contém contas; `Conta` contém `Histórico`  

---

## ▶️ Como executar
1️⃣ Certifique-se de ter o **Python 3.10+** instalado.  
2️⃣ Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio

---

3️⃣ Execute o programa:
python banco1_poo.py

---

🖥️ Exemplo do menu (CLI)
=============== MENU ================
[d] Depositar
[s] Sacar
[e] Extrato
[nc] Nova conta (corrente ou poupança)
[lc] Listar contas
[nu] Novo usuário
[q] Sair
=>

---

🚀 Melhorias futuras
Integração com interface gráfica (Tkinter ou Web)

Armazenamento em arquivo ou banco de dados

Suporte a contas jurídicas

Autenticação de usuários com senha

---

👨‍💻 Autor
Feito com 👨‍💻  por Paulo Henrique de Andrade
