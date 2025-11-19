# neolider-sistema-interno
# 🏭 Sistema Interno de Consulta e Requisições de Estoque — Neolider

Sistema interno desenvolvido para facilitar a consulta e o gerenciamento de requisições de estoque dentro da empresa Neolider.  
O sistema possui uma hierarquia de permissões por cargo, garantindo segurança, controle e organização no fluxo de materiais.

---

## 🚀 Funcionalidades Principais

###  **Login com níveis de acesso**
O sistema possui diferentes permissões de acordo com o cargo:
- **CEO / Administrador**: pode visualizar e criar requisições para qualquer setor.
- **Gestores**: podem criar requisições apenas do seu setor.
- **Funcionários**: podem apenas consultar o estoque.
- **Usuários limitados**: acesso somente a consultas específicas.

---

##  Funcionalidades
- Consulta completa de estoque
- Cadastro de requisições por setor
- Histórico de requisições
- Controle de usuários por cargo
- Interface simples e intuitiva em Java Swing
- Estrutura modular para expansão futura

---

## Tecnologias Utilizadas
- **Java (JDK 17+)**
- **Swing** para interface gráfica
- **POO (Programação Orientada a Objetos)**
- Banco de dados *(caso utilize futuramente — MySQL recomendado)*

---

## 📁 Estrutura do Projeto (Exemplo)
/src
/neolider
/programainterno
Estoque.java
Requisicoes.java
Usuario.java
Login.java
Main.java
