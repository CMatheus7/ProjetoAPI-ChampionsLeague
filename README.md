# ⚽ API de Jogadores e Clubes

API REST simples para consulta de **jogadores** e **clubes** de futebol.  
Desenvolvida com **Node.js** e **Fastify**, ideal para testes, estudos ou integração com outros sistemas.

---

## 🚀 Tecnologias Utilizadas
- **Node.js** — Ambiente de execução JavaScript
- **Fastify** — Framework rápido para criação de APIs
- **JavaScript (ESM)** — Módulos nativos do JavaScript

---

## 📂 Estrutura do Projeto


src/
- ├── index.js # Ponto de entrada do servidor
- ├── routes/ # Definição das rotas
- ├── controllers/ # Lógica de negócio das rotas
- └── utils/ # Funções auxiliares



---

## 📡 Endpoints Disponíveis

### **1️⃣ Listar Jogadores**
- **Rota:** `GET /api/players`
- **Descrição:** Retorna todos os jogadores cadastrados.
- **Exemplo de Resposta:**


## json


 -   { "id": 1, "name": "Lionel Messi", "club": "Inter Miami" },
 -  { "id": 2, "name": "Cristiano Ronaldo", "club": "Al Nassr" }



## Teste via cURL:

- curl -X GET http://localhost:3333/api/players

## Listar Clubes
- Rota: GET /api/clubs

## Descrição: Retorna todos os clubes cadastrados.

- Exemplo de Resposta:


-   { "id": 1, "name": "Real Madrid" },
-  { "id": 2, "name": "Barcelona" }


## ▶️ Como Executar o Projeto
- Clonar o repositório

## Instalar as dependências

- npm install

## Iniciar o servidor

- npm start

## Ou no modo de desenvolvimento:
npm run dev

# Acessar no navegador

http://localhost:3333/api/players

http://localhost:3333/api/clubs

## 📌 Observações
Certifique-se de que a porta 3333 esteja livre antes de iniciar o servidor.

- A API utiliza dados estáticos para demonstração, mas pode ser integrada a um banco de dados.

## 📜 Licença
Este projeto é open-source e está disponível para uso livre, modificação e distribuição.


Esse modelo já está **documentado para uso real**, com **exemplos de resposta, cURL e instruções de execução**.  



