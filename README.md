# 🔐 Sistema de Autenticação de Usuários — IESB

Este projeto foi desenvolvido como parte de uma atividade acadêmica da disciplina de **Construção de Back-end**, com o objetivo de praticar conceitos de autenticação, controle de acesso e manipulação de arquivos utilizando **Python puro**.

A proposta do sistema é simular um módulo de autenticação de usuários de um sistema acadêmico-administrativo do **IESB**, permitindo o **cadastro**, **login** e **controle básico de acesso** dos usuários.

---

## 🎯 Objetivo do Projeto

Desenvolver apenas a **parte de back-end** de um sistema web de autenticação, contendo:

- Cadastro de usuários  
- Login de usuários  
- Validação de credenciais  
- Armazenamento seguro de dados  
- Controle de acesso básico  

Tudo isso utilizando apenas Python, sem frameworks externos.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x  
- Bibliotecas padrão do Python   
- Manipulação de arquivos `.txt` para persistência de dados  

---

## ⚙️ Funcionalidades

### 1️⃣ Cadastro de Usuário
- O usuário informa um nome de usuário e uma senha.
- O sistema verifica se o usuário já existe:
  - Se **não existir**, ele é cadastrado com sucesso.
  - Se **já existir**, o sistema informa que o cadastro já está registrado.

### 2️⃣ Login
- O usuário informa login e senha.
- O sistema valida as credenciais:
  - Se estiverem corretas → `Login realizado com sucesso. Bem-vindo!`
  - Se estiverem incorretas → `Erro. Usuário ou senha inválidos.`

### 3️⃣ Sair do Sistema
- O usuário escolhe a opção `3` para encerrar o programa.
- O sistema exibe a mensagem `Saindo do programa...`.

### 4️⃣ Opção Inválida
- Caso o usuário digite uma opção que não exista no menu, o sistema exibe uma mensagem de opção inválida.

---

## 🔒 Segurança

- As senhas **não são armazenadas em texto puro**.
- Elas são codificadas antes de serem salvas, garantindo que os dados sensíveis não fiquem expostos no arquivo.

---

## 💾 Armazenamento dos Dados

Os dados dos usuários são armazenados em um arquivo chamado:


Nesse arquivo ficam registrados os usuários e suas respectivas senhas codificadas.

---

