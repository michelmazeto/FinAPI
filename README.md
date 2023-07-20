# <p style="font-size: 36px; font-weight: bold; text-align: left;">FinAPI</p>
✅ **Project Completed**

## Overview
🚀 FinAPI is a very simple API that performs withdrawals/deposits

## Prerequisites
Before you begin, ensure you have the following tools installed on your machine:
- ✔️ [Git](https://git-scm.com)
- ✔️ [Node.js](https://nodejs.org/en/)

You'll also need a code editor like [VSCode](https://code.visualstudio.com/) to work with the code.

## Running the API (Server)


🔽 Clone this repository
```bash
$ git clone <https://github.com/michelmazeto/FinAPI.git>
````

📂 Navigate to the project folder in the terminal
```bash
$ cd finapi
```

💻 Install the necessary dependencies
```bash
$ npm install
# If you prefer using yarn
$ yarn
```

🚀 Start the application in development mode
```bash
$ yarn dev
# If using npm
$ npm run dev
```

🌐 The server will start on port 3333 - access <http://localhost:3333>

---

## Requirements
- ✔️ Ability to create an account
- ✔️ Ability to retrieve client's bank statement
- ✔️ Ability to make deposits
- ✔️ Ability to make withdrawals
- ✔️ Ability to view bank statement by date
- ✔️ Ability to update account information
- ✔️ Ability to obtain account details
- ✔️ Ability to delete an account
- ✔️ Ability to check account balance

## Business Rules
- ✔️ Prevent registration of accounts with existing CPFs
- ✔️ Handle retrieval of statements from non-existent accounts
- ✔️ Restrict deposits to existing accounts only
- ✔️ Prohibit withdrawals from non-existent accounts
- ✔️ Enforce minimum balance for withdrawals
- ✔️ Prevent deletion of non-existent accounts

---
## Technologies Used

The following technologies were used in building this project:

- 🟢 [Node.js](https://nodejs.org/en/)
- 🔵 [Express.js](https://expressjs.com)

---

<div align="center">
  <p style="font-size: 14px; color: #60a360;">
    <em>Note: This project was developed based on a course by Rocketseat.</em>
  </p>
</div>
