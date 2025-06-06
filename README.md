# 🍕 PizzaShop API

Back-end de um site de gestão de pizzarias, em que o dono da pizzaria consegue acompanhar todo o processo de venda e desempeho da empresa, desenvolvido com **TypeScript**, **Drizzle** e **ElysiaJS**.

> Este projeto foi desenvolvido com o curso da Rockeseat, com o objetivo de ser independente ao ambiente de execução, ou seja, ele pode rodar em **Bun**, **Node.js**, **Cloudflare Workers** ou qualquer ambiente compatível com APIs Web padrão.

---

## ▶️ Como executar

Este projeto depende do **Docker** para configurar o banco de dados.

Com o Docker instalado, siga os passos abaixo:

```bash
# Instale as dependências
bun i
```
```bash
# Inicie os containers do banco de dados
docker compose up -d
```
```bash
# Rode as migrações para criar as tabelas
bun migrate
```
```bash
# Popule o banco com dados fictícios
bun seed
```
```bash
# Inicie o servidor de desenvolvimento
bun dev
```
## Funcionalidades

**Resumo** das funcionalidades:

- Deve ser possível **registrar um novo restaurante**
- Deve ser possível **fazer login como gerente do restaurante**
- Deve ser possível **se cadastrar como um novo cliente**
- Deve ser possível **criar um pedido para o restaurante**
- Deve ser possível **gerenciar o cardápio do restaurante**
- Deve ser possível **gerenciar as avaliações do restaurante**
- Deve ser possível **deixar uma avaliação**
- Deve ser possível **gerenciar os pedidos do restaurante**
- Deve ser possível **atualizar o perfil público do restaurante**
- Deve ser possível **abrir/fechar o restaurante**
- Deve ser possível **listar métricas do restaurante**

