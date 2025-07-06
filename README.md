# 🧪 Store API - TDD com FastAPI

Uma API de produtos desenvolvida com **FastAPI** e **MongoDB**, utilizando **TDD (Test Driven Development)** como metodologia principal. Este projeto tem fins **educativos**, voltado para o aprendizado prático de testes com **Pytest**, validação com **Pydantic** e uso do banco de dados **MongoDB** com **Motor**.

---

## 📌 Objetivo

Aplicar na prática o conceito de TDD (Desenvolvimento Orientado a Testes), utilizando a stack:

- **FastAPI** – Criação da API;
- **Pydantic** – Validação de dados;
- **MongoDB + Motor** – Persistência de dados;
- **Pytest** – Criação dos testes automatizados;

---

## 🧪 O que é TDD?

**TDD (Test Driven Development)** é uma prática de desenvolvimento onde os testes são escritos **antes mesmo da implementação do código**. O ciclo básico do TDD é:

1. ✳️ Escreva um teste que falha;
2. 🛠️ Implemente a funcionalidade para passar no teste;
3. 🔁 Refatore o código mantendo os testes verdes.

### ✅ Vantagens:
- Código mais limpo e objetivo;
- Alta cobertura de testes;
- Identificação precoce de falhas;
- Confiança na refatoração;
- Evita deixar testes para depois (ou nunca fazer).

---

## 🏗️ Arquitetura

O projeto segue uma arquitetura em camadas com divisão clara entre:

- Schemas (validação de dados com Pydantic);
- Usecases (regras de negócio);
- Controllers (rotas e integração com a API);
- Repositórios (acesso ao banco de dados com Motor);
- Testes automatizados com Pytest.

---

## 🔍 Funcionalidades da API

- ✅ Criar produto
- ✅ Listar todos os produtos
- ✅ Buscar produto por ID
- ✅ Atualizar produto
- ✅ Deletar produto
- ✅ Filtro por preço (ex: `5000 < preço < 8000`)

---
