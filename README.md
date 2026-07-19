# Reciprocity

<p align="center">
  <img src="./docs/banner.png" alt="Reciprocity">
</p>

<h3 align="center">
Uma plataforma onde habilidades se transformam em oportunidades.
</h3>

---

## Sobre o Projeto

O **Reciprocity** é uma plataforma de troca de serviços que conecta pessoas com diferentes habilidades, permitindo que elas colaborem entre si sem a necessidade de utilizar dinheiro.

A ideia nasceu a partir de um problema comum: muitas pessoas possuem conhecimentos e talentos, mas não conseguem acessar determinados serviços por limitações financeiras.

Com o Reciprocity, usuários podem oferecer suas habilidades, encontrar serviços disponíveis e criar conexões baseadas na colaboração.

---

## Objetivo

Criar uma plataforma simples, segura e organizada para facilitar a troca de serviços entre pessoas.

O projeto busca incentivar:

-  Economia colaborativa
-  Conexões entre comunidades
-  Valorização de habilidades individuais

---

## Problema

Muitas pessoas possuem habilidades que poderiam ajudar outras, porém não possuem recursos financeiros para contratar determinados profissionais.

O Reciprocity transforma conhecimento e experiência em uma forma de troca de valor.

---

## MVP

A primeira versão da plataforma terá:

### Usuários
- Cadastro de conta
- Login
- Perfil do usuário

### Serviços
- Cadastro de serviços
- Visualização de serviços disponíveis
- Busca por habilidades

### Trocas
- Solicitação de troca
- Aceitar ou recusar propostas
- Acompanhamento das solicitações

---

## Tecnologias

### Frontend
- React
- TypeScript

### Backend
- Node.js
- Express

### Banco de Dados
- PostgreSQL

### ORM
- Prisma

### Comunicação
- API REST

---

# How Reciprocity Works

```mermaid
flowchart LR

A[Create Account]
--> B[Create Profile]

B --> C[Publish Service]

C --> D[Search Services]

D --> E[Request Exchange]

E --> F{Accept or Reject}

F -->|Accept| G[Collaboration]

F -->|Reject| H[Request Closed]


