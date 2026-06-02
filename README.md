# 🔐 Sistema com Login Integrado

Sistema desenvolvido com **PHP, Java e MySQL**, contendo autenticação de usuários e integração entre login e tela de cadastro, garantindo controle de acesso e segurança dos dados.

---

## 📌 Objetivo

Implementar um sistema de login funcional que valide usuários no banco de dados e permita o acesso somente mediante credenciais corretas, além de enviar o nome do usuário logado para outras telas do sistema.

---

## 🚀 Funcionalidades

- 🔑 Formulário de login (usuário/e-mail e senha)
- 🧠 Validação de credenciais no banco de dados
- 🛑 Bloqueio de acesso com dados inválidos
- 👤 Identificação do usuário logado
- 📤 Envio do nome do usuário para a tela de cadastro
- 📋 Exibição: “Usuário logado: Nome”
- 🔒 Uso de consultas seguras (Prepared Statements)
- ⚠️ Tratamento de erros de conexão com o banco

---

## 🧱 Estrutura do Sistema

- **PHP (Web)** → Responsável pelo login e validação
- **Java (Desktop)** → Tela de cadastro com exibição do usuário logado
- **MySQL** → Armazenamento de usuários e autenticação

---

## 🗄️ Banco de Dados

Tabela: `usuarios`

Exemplo de dados:

- admin / 123
- joao / 123
- maria / 123

---

## 🔄 Fluxo do Sistema

1. Usuário acessa a tela de login  
2. Informa usuário e senha  
3. Sistema valida no banco de dados  
4. Se válido, libera acesso  
5. Nome do usuário é enviado para a tela de cadastro  
6. Interface exibe: **Usuário logado: Nome**

---

## 🛠️ Tecnologias Utilizadas

- PHP
- Java (Swing ou Desktop)
- MySQL
- JDBC / PDO
- SQL

---

## 🔒 Segurança

- Uso de consultas preparadas (Prepared Statements)
- Validação de dados no backend
- Controle de acesso por autenticação

---

## 👨‍💻 Autor

Desenvolvido por **Vinicius Felipe**

## ⚙️ Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/ViniciusFelipi/Confeitaria-Cosmo-Cakes.git
