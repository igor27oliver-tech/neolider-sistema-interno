# neolider-sistema-interno

🏭 **Sistema Interno de Consulta e Requisições de Estoque — Neolider**

Sistema interno desenvolvido para facilitar a consulta e o gerenciamento de requisições de estoque dentro da empresa **Neolider**.  
Possui uma hierarquia de permissões por cargo, garantindo segurança, organização e controle no fluxo de materiais.

---

## 🚀 Funcionalidades Principais

### 🔐 Login com níveis de acesso
O sistema possui diferentes permissões conforme o cargo do usuário:

- **CEO / Administrador:** pode visualizar e criar requisições para qualquer setor.
- **Gestores:** podem criar requisições somente do próprio setor.
- **Funcionários:** podem apenas consultar o estoque.
- **Usuários limitados:** acesso restrito a consultas específicas.

---

## 📦 Outras Funcionalidades

- Consulta completa de estoque  
- Cadastro de requisições por setor  
- Histórico de requisições realizadas  
- Controle de usuários e permissões  
- Interface simples e intuitiva desenvolvida em **Java Swing**  
- Arquitetura modular, permitindo expansão futura  

---

## 🛠️ Tecnologias Utilizadas

- **Java (JDK 17+)**
- **Swing** (interface gráfica)
- **POO – Programação Orientada a Objetos**
- *(Futuro)* Banco de dados — recomendado **MySQL**

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
