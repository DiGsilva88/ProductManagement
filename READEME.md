# ProductManagement — Fase 1

## Objetivo

Desenvolver uma aplicação em C# utilizando **Arquitetura em Camadas** para gestão de produtos.

Nesta primeira fase, a aplicação deverá permitir:

- adicionar produtos
- listar produtos
- procurar produtos por nome
- remover produtos

---

# Arquitetura do Projeto

A solution deverá estar organizada em camadas:

```text
ProductManagement
│
├── ProductManagement.UI
├── ProductManagement.Business
├── ProductManagement.Data
└── ProductManagement.Domain
```

---

# Responsabilidade de cada camada

| Camada | Responsabilidade |
|---|---|
| UI | interação com o utilizador |
| Business | regras de negócio |
| Data | armazenamento e acesso aos dados |
| Domain | entidades e interfaces |

---

# Funcionalidades

## Adicionar produto

Permitir registar um produto com:
- nome
- preço

---

## Listar produtos

Apresentar todos os produtos registados.

---

## Procurar produto por nome

Permitir pesquisar um produto através do nome.

---

## Remover produto

Permitir remover um produto através do seu Id.

---



# Regras de negócio

As validações devem ficar na Business Layer.

## Regras obrigatórias

- nome não pode ser vazio
- preço deve ser superior a zero

---

# Menu esperado

```text
1 - Adicionar produto
2 - Listar produtos
3 - Procurar produto
4 - Remover produto
0 - Sair
```

---

# Objetivos pedagógicos

Este projeto pretende desenvolver:

- arquitetura em camadas
- separação de responsabilidades
- utilização de interfaces
- organização de código
- reutilização
- desacoplamento entre componentes

---

# Tecnologias utilizadas

- C#
- .NET
- Console Application

---

# Notas importantes

## Interface Layer

Responsável apenas por:
- mostrar menus
- recolher dados
- apresentar resultados

---

## Business Layer

Responsável por:
- validações
- regras de negócio
- comunicação com repositórios

---

## Data Layer

Responsável por:
- guardar produtos
- remover produtos
- procurar produtos
- devolver listas de dados

---

