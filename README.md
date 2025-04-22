# Teste Prático – Programador

## Objetivo

Este teste tem como objetivo avaliar seus conhecimentos em backend, frontend, estilização, conexão com banco de dados e controle de versão com Git. A seguir, você encontrará os requisitos para a criação de uma aplicação simples que deve ser entregue dentro de um prazo de 5 dias.

---

## Enunciado

Crie uma aplicação web que permita ao usuário cadastrar e listar "tarefas". A aplicação deverá ser composta por um **frontend** em React, com estilização em **CSS**, e um **backend** que pode ser feito utilizando **Node.js (Express)** ou **PHP** para gerenciar as requisições de cadastro e listagem das tarefas. O backend deve se conectar a um banco de dados **MySQL** para persistir os dados.

### Requisitos:

#### 1. Backend (Node.js / Express ou PHP)
- **Node.js (Express)**:
  - Crie um servidor Node.js usando o Express.
  - O servidor deve permitir duas rotas:
    - `GET /tarefas`: Retorna uma lista de todas as tarefas cadastradas no banco de dados.
    - `POST /tarefas`: Permite o cadastro de uma nova tarefa, contendo pelo menos o **nome** e a **descrição**.
  - Use um banco de dados MySQL para armazenar as tarefas. Crie uma tabela chamada `tarefas` com as colunas `id`, `nome`, `descricao` e `data_criacao`.
  - Utilize **Querys SQL** para interagir com o banco de dados.
  
- **PHP**:
  - Crie um servidor PHP com um endpoint que implemente a mesma lógica descrita abaixo.
  - O servidor deve permitir duas rotas:
    - `GET /tarefas`: Retorna uma lista de todas as tarefas cadastradas no banco de dados.
    - `POST /tarefas`: Permite o cadastro de uma nova tarefa, contendo pelo menos o **nome** e a **descrição**.
  - Use um banco de dados MySQL para armazenar as tarefas. Crie uma tabela chamada `tarefas` com as colunas `id`, `nome`, `descricao` e `data_criacao`.
  - Utilize **Querys SQL** para interagir com o banco de dados.
  - Para implementação em PHP, o uso de **PDO** para conectar ao banco de dados é altamente recomendado.

#### 2. Frontend (React)
- Crie uma interface simples para:
  - Exibir uma lista de tarefas.
  - Permitir o cadastro de uma nova tarefa.
- A lista de tarefas deve ser exibida de forma simples, mostrando o nome e a descrição de cada tarefa.
- A página de cadastro de tarefas deve ter um formulário com campos para o nome e a descrição da tarefa.

#### 3. Estilização (CSS)
- Estilize a interface utilizando CSS para garantir que a aplicação tenha uma boa aparência, com elementos como botões, inputs e listas.
- Utilize boas práticas de organização do CSS, como classes reutilizáveis e uso de seletores adequados.

#### 4. Banco de Dados (MySQL)
- Crie um banco de dados no MySQL e configure as credenciais no servidor backend (Node.js ou PHP).
- Faça a conexão com o banco de dados para salvar e listar as tarefas.
- Utilize comandos SQL para criar a tabela e fazer as inserções e consultas.

#### 5. Git
- Crie um repositório Git para armazenar seu código.
- Faça commits frequentes durante o desenvolvimento do projeto, com mensagens claras de alteração.

---

## Resultado Esperado

A aplicação deve funcionar corretamente, permitindo que o usuário:
- Cadastre tarefas e as visualize na tela.
- As tarefas devem ser armazenadas em um banco de dados MySQL.
- O frontend deve estar estilizado de forma limpa e funcional.

## Critérios de Avaliação

- **Funcionalidade:** A aplicação deve funcionar corretamente de acordo com os requisitos (cadastro e listagem de tarefas).
- **Boas práticas de codificação:** Código bem estruturado, modularizado e legível.
- **Uso adequado do Git:** Repositório Git com commits claros e frequentes.
- **Estilização:** A interface deve ser agradável e funcional.
- **Conexão com banco de dados:** A aplicação deve ser capaz de persistir e recuperar dados do banco de dados MySQL.

---

## Instruções Adicionais

- Você pode escolher entre **Node.js (Express)** ou **PHP** para o desenvolvimento do backend. Ambas as opções são válidas, e o foco será avaliar sua compreensão de como criar um backend simples, interagir com um banco de dados e integrá-lo ao frontend.
- Certifique-se de que o código seja bem organizado e fácil de entender. Comentários explicativos são sempre bem-vindos.

## Instruções de Entrega

- Crie um repositório privado para hospedar seu trabalho.

- Comite seu código frequentemente e de forma clara. Certifique-se de que o código esteja bem estruturado e funcional.

- Envie o link do repositório Git por email ou whatsapp para oficializar a entrega.

