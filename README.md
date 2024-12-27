# 📊 Backend - Sistema de Gestão Financeira

## 📝 **Descrição do Projeto**
Este projeto é o backend de um sistema de gestão financeira desenvolvido com **NestJS**. Ele fornece APIs para gerenciar receitas, despesas e gerar relatórios filtrados por data e faixa de valores. O banco de dados utilizado é **SQLite** com **TypeORM**.

---

## 🚀 **Tecnologias Utilizadas**
- **Node.js**
- **NestJS**
- **TypeScript**
- **TypeORM**
- **SQLite**
- **JWT (JSON Web Token)**

---

## 📂 **Estrutura de Pastas**

```
backend/
│
├── src/
│   ├── auth/        # Autenticação e proteção de rotas
│   ├── income/      # Gerenciamento de receitas
│   ├── expense/     # Gerenciamento de despesas
│   ├── report/      # Geração de relatórios
│   ├── app.controller.ts
│   ├── app.module.ts
│   ├── app.service.ts
│   └── main.ts
│
├── .env             # Variáveis de ambiente
├── .gitignore       # Arquivos ignorados pelo Git
├── package.json     # Dependências do projeto
├── tsconfig.json    # Configuração do TypeScript
├── README.md        # Documentação do backend
└── database.db      # Banco de dados SQLite
```

---

## ⚙️ **Configuração do Ambiente**

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd backend
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```


3. **Execute as migrações do banco de dados:**
   ```bash
   npm run typeorm migration:run
   ```

4. **Inicie o servidor:**
   ```bash
   npm run start:dev
   ```

5. **Acesse a API:**
   - **URL base:** `http://localhost:3000`

---

## 🔑 **Autenticação**
- Utilize JWT para autenticação das rotas protegidas.
- Envie o token no cabeçalho `Authorization` como `Bearer <token>`.

---

## 📊 **Relatórios**
- Geração de relatórios filtrados por:
   - Data inicial e final
   - Faixa de valores
- O relatório é exportado em formato **Excel**.

---

## ✅ **Endpoints Principais**

- **Receitas:** `/incomes`
- **Despesas:** `/expenses`
- **Relatórios:** `/reports`

---


## 🤝 **Contribuição**
Sinta-se à vontade para contribuir enviando Pull Requests.

---

## 📄 **Licença**
Este projeto está sob a licença **MIT**.

---

Feito por [Lucas Dellis](https://github.com/DellisLucas). 🚀✨

