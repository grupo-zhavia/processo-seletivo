# Sistema de Gerenciamento de Tarefas para Equipes

## Descrição do Projeto

Desenvolver um sistema básico de gerenciamento de tarefas onde os usuários podem criar, atualizar e visualizar tarefas.

## Requisitos Técnicos

- **Frontend:** NextJS
- **Backend:** NestJS
- **Banco de Dados:** PostgreSQL (relacional) e MongoDB (não relacional)
- **Arquitetura:** Microsserviços
- **Metodologia:** TDD (Test-Driven Development)

### Escopo Reduzido

**Frontend:**

- Interface para visualizar e criar tarefas.
- Implementação básica de autenticação.
- **Documentação:** Design da interface e bibliotecas utilizadas.

**Backend:**

- Microsserviço para gerenciamento de tarefas com endpoints CRUD.
- Implementação básica de autenticação.
- Testes unitários para as principais funcionalidades.
- **Documentação:** Arquitetura dos microsserviços e testes implementados.

**Banco de Dados:**

- PostgreSQL para tarefas.
- MongoDB para logs de alterações.
- **Documentação:** Estrutura dos bancos de dados.

**Diferenciais:**

- Implementação de notificações em tempo real (WebSockets).
- Sistema de permissões e roles para usuários.
- Dashboard de analytics para visualização de métricas de uso.
