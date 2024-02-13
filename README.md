API RESTfull com NodeJS, com uso de frameworks e bibliotecas externas.

Neste projeto foram utilizados:
- `Fastify`
- `TypeScript`
- `ESLint`
- `Knex`
- `Zod`
- `SQLite`
- `Cookies`
- `Testes E2E com Vitest`

## 💻 Pré-requisitos

Para rodar o projeto é necessário ter instalado:

- `NodeJS`
- `Npm`
- `Insomnia` ou similares


## 🚩 Instalando Dependências

Para instalar as dependências da aplicação, execute:

```
npm install
```


## 📜 Migrations

Para executar as migrations, execute:

```
npm run knex -- migrate:latest
```

## 🚀 Executando

Para rodar a aplicação, execute:

```
npm run dev
```

## 🚦 Testes

Para rodar os testes da aplicação, execute:

```
npm test
```

## 💾 Arquivos

O arquivo `Insomnia_2024_02_13.json`, na raiz do projeto, é para a importação das rotas desta API no Insomnia.



# RF
- [x] O usuário deve poder criar uma nova transação
- [x] O usuário deve poder obter um resumo da sua conta
- [x] O usuário deve poder listar todas as transação que já ocorreram
- [x] O usuário deve poder visualizar uma transação única

# RN
- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá
- [x] Deve ser possível identificarmos o usuário entre as requisições
- [x] O usuário só pode visualizar transações o qual ele criou

