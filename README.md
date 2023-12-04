# Node Wallet API

The NodeWallet API is a straightforward yet robust application developed in Node.js with the assistance of powerful frameworks such as Fastify, Knex, and Vitest. This API is designed to provide a seamless financial transaction experience without the need to create an account. Upon accessing the API, a UUID is generated and stored in the user's cookies for identification.

 - `Simple Transactions:` Users can perform credit and debit transactions in their accounts. The "credit" option adds funds to the account, while "debit" withdraws them.

 - `Balance and Summary:` A dedicated endpoint provides users with a detailed summary of their account, including the current balance. This offers an instant overview of finances.

 - `Transaction History:` Users have the ability to list all transactions associated with their account. This provides a complete record of financial activities.

 - `Transaction Query:` An endpoint allows users to retrieve specific details about a transaction, using the unique ID assigned to each transaction.

 - `Automated Testing:` The project is accompanied by a robust suite of automated tests developed with Vitest. This ensures ongoing stability and reliability of the API.

## ✨ Features
 - The user can create a new transaction
 - The user can get an account summary
 - The user can list all previously conducted transactions
 - The user can view a specific transaction by id

## 💻 Installation

- Install Node and NPM

```bash
  npm install
```

- Run the migrations

```bash
  npm run knex -- migrate:latest
```

 - Run "build", to create the js files

```bash
  npm run build
``` 

## 🚀 Getting started

 - Run the project

```bash
  node build/server.js
``` 

## 📝 Examples
 - To create an transaction

```bash
  {
    "title": "Work",
    "amount": 2000,
    "type": "credit"
  }
``` 