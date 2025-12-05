# Fastify CRUD

![Fastify](https://img.shields.io/badge/Fastify-FF3E00?style=for-the-badge&logo=fastify&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Projeto back-end:** CRUD completo desenvolvido com **Fastify**, focado em performance, boas práticas de código e construção de APIs RESTful escaláveis. Este projeto serve como estudo de Fastify, desenvolvimento de APIs rápidas e escaláveis, e apresentação em portfólio.

O repositório implementa funcionalidades de **CRUD (Create, Read, Update, Delete)**, permitindo praticar criação de APIs RESTful, validação de dados, conexão com banco de dados PostgreSQL e organização modular de código.

## Tecnologias usadas
- Node.js  
- Fastify  
- TypeScript  
- PostgreSQL  
- [Adicionar outras dependências se houver, ex.: Prisma, Zod]

## Estrutura do projeto
src/
├─ controllers/ # Rotas da API
├─ services/ # Lógica de negócio
├─ dtos/ # Validação de dados
├─ database/ # Configuração do banco
├─ server.ts # Ponto de entrada do projeto

Estrutura modular, organizada e escalável, facilitando manutenção.

## Funcionalidades e Endpoints

| Método | Rota          | Descrição                 | Exemplo de payload |
|--------|---------------|---------------------------|------------------|
| POST   | `/items`      | Criar novo item           | `{ "nome": "Item A", "descricao": "Descrição do item" }` |
| GET    | `/items`      | Listar todos os itens     | - |
| GET    | `/items/:id`  | Buscar item por ID        | - |
| PATCH  | `/items/:id`  | Atualizar item            | `{ "nome": "Item Atualizado" }` |
| DELETE | `/items/:id`  | Deletar item              | - |

Os DTOs garantem que os dados recebidos estejam validados antes de serem processados.

## Como rodar
1. Clone o repositório:
```bash
git clone https://github.com/Weslley414/fastify-crud.git
