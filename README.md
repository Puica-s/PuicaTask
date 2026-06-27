# MVP de Lista de Organização de Tarefas

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um MVP (Minimum Viable Product) de uma aplicação web para organização e gerenciamento de tarefas, utilizando conceitos de Engenharia de Software e metodologias ágeis.

A aplicação foi desenvolvida com HTML, CSS e JavaScript, permitindo ao usuário cadastrar, editar, excluir e concluir tarefas de forma simples e intuitiva.

O projeto teve como foco a aplicação prática de conceitos relacionados a Scrum, Kanban, backlog do produto e desenvolvimento incremental.

---

# Objetivos

## Objetivo Geral

Desenvolver uma aplicação simples para gerenciamento de tarefas, permitindo:

* Cadastro de tarefas;
* Edição de tarefas;
* Exclusão de tarefas;
* Conclusão de tarefas;
* Filtragem de tarefas.

---

# Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript
* LocalStorage

---

# Metodologias Ágeis Aplicadas

## Scrum

O Scrum foi utilizado para organização do desenvolvimento em sprints, permitindo divisão das atividades e acompanhamento da evolução do projeto.

### Sprint 1

* Cadastro de tarefas;
* Listagem de tarefas;
* Conclusão de tarefas.

### Sprint 2

* Edição de tarefas;
* Exclusão de tarefas;
* Filtros;
* Melhorias visuais.

---

## Kanban

O Kanban foi utilizado para acompanhamento visual das tarefas por meio de colunas como:

* To Do
* Doing
* Done

---

# Funcionalidades Implementadas

## Cadastro de Tarefas

Permite adicionar novas tarefas à lista.

## Edição de Tarefas

Permite alterar informações de tarefas já cadastradas.

## Exclusão de Tarefas

Permite remover tarefas da lista.

## Conclusão de Tarefas

Permite marcar tarefas como concluídas.

## Filtro de Tarefas

Permite visualizar:

* Todas as tarefas;
* Tarefas concluídas;
* Tarefas pendentes.

## Persistência de Dados

As tarefas são armazenadas utilizando LocalStorage, permitindo manter os dados mesmo após atualizar a página.

---

# Estrutura do Projeto

```bash
📁 projeto-lista-organizacao
│
├── 📁 css
│   └── style.css
│
├── 📁 js
│   └── script.js
│
├── index.html
└── README.md
```

---

# Backlog Inicial

## Planejamento

* #1 Definir escopo do MVP
* #2 Levantar requisitos funcionais
* #3 Criar histórias de usuário
* #4 Criar protótipo no Figma

## Setup

* #5 Criar estrutura inicial do projeto
* #6 Organizar estrutura de pastas
* #7 Criar README inicial

## Funcionalidades

* #8 Implementar cadastro de tarefas
* #9 Implementar listagem de tarefas
* #10 Implementar conclusão de tarefas
* #11 Implementar edição de tarefas
* #12 Implementar exclusão de tarefas
* #13 Implementar filtros de tarefas

## Persistência

* #14 Salvar tarefas no LocalStorage
* #15 Carregar tarefas do LocalStorage

## Qualidade

* #16 Realizar testes manuais
* #17 Corrigir bugs e ajustar interface

## Documentação

* #18 Capturar screenshots da aplicação
* #19 Elaborar relatório do projeto
* #20 Preparar apresentação

---

# Histórias de Usuário

## US01 — Cadastro de Tarefas

**Como** usuário,
**quero** cadastrar tarefas,
**para** organizar minhas atividades diárias.

---

## US02 — Listagem de Tarefas

**Como** usuário,
**quero** visualizar minhas tarefas em uma lista,
**para** acompanhar minhas atividades cadastradas.

---

## US03 — Conclusão de Tarefas

**Como** usuário,
**quero** marcar tarefas como concluídas,
**para** acompanhar meu progresso.

---

## US04 — Edição de Tarefas

**Como** usuário,
**quero** editar tarefas existentes,
**para** corrigir ou atualizar informações.

---

## US05 — Exclusão de Tarefas

**Como** usuário,
**quero** excluir tarefas,
**para** remover atividades que não são mais necessárias.

---

## US06 — Filtro de Tarefas

**Como** usuário,
**quero** filtrar tarefas por status,
**para** visualizar apenas tarefas concluídas ou pendentes.

---

# Critérios de Aceitação

## US01 — Cadastro de Tarefas

* O usuário deve conseguir adicionar uma nova tarefa.
* A tarefa cadastrada deve aparecer na lista imediatamente.

## US02 — Listagem de Tarefas

* O sistema deve exibir todas as tarefas cadastradas.
* As tarefas devem permanecer visíveis após atualização da página.

## US03 — Conclusão de Tarefas

* O usuário deve conseguir marcar uma tarefa como concluída.
* Tarefas concluídas devem possuir diferenciação visual.

## US04 — Edição de Tarefas

* O usuário deve conseguir alterar o texto de uma tarefa existente.
* As alterações devem ser salvas corretamente.

## US05 — Exclusão de Tarefas

* O usuário deve conseguir remover tarefas da lista.
* A tarefa excluída não deve mais aparecer na interface.

## US06 — Filtro de Tarefas

* O usuário deve conseguir visualizar:

  * Todas as tarefas;
  * Apenas tarefas concluídas;
  * Apenas tarefas pendentes.

---

# Resultados Obtidos

O MVP atingiu os objetivos propostos, apresentando funcionamento adequado das funcionalidades principais.

Entre os pontos positivos destacam-se:

* Interface simples;
* Facilidade de uso;
* Organização das tarefas;
* Aplicação prática de metodologias ágeis.

Como limitação do projeto:

* Não possui banco de dados online;
* Não possui autenticação de usuários.

---

# Melhorias Futuras

* Integração com banco de dados;
* Sistema de login;
* Responsividade para dispositivos móveis;
* Categorias de tarefas;
* Prioridades e prazos;
* Integração com APIs.


SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.
