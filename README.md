# 📝 Sistema de Login e Cadastro em Java

Este projeto é um sistema simples com duas telas: uma de **login** e outra de **cadastro de usuários**. Desenvolvido com **Java**, usando **Swing** para a interface gráfica e **JDBC** para integração com banco de dados.

---

## 🚀 Funcionalidades

- Tela de login com validação de usuário e senha
- Tela de cadastro com:
  - Inserção de novos usuários
  - Edição de usuários existentes
  - Exclusão de registros
  - Busca por ID
  - Listagem de todos os dados
- Navegação entre telas (login → cadastro)
- Integração com banco de dados MySQL (ou outro via JDBC)

---

## 🛠️ Tecnologias utilizadas

- Java (JDK)
- Swing (interface gráfica)
- JDBC (conexão com banco)
- MySQL (ajustável para SQLite/PostgreSQL)

---

## 📁 Estrutura do Projeto

| Classe                   | Função                                                                 |
|--------------------------|------------------------------------------------------------------------|
| `Conexao.java`           | Realiza a conexão com o banco de dados                                 |
| `acoes.java`             | Executa a ação de salvar novo usuário no banco                         |
| `tela_de_acesso.java`    | Tela inicial para login. Redireciona à tela de cadastro se login for válido |
| `Tela_cadastro.java`     | Interface principal com funcionalidades de CRUD                        |

---
