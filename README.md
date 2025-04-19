# Team5
# 🛡️ CyberGuard Innovations — Neucron Wallet & Transaction CLI

A CLI tool built with the [Neucron SDK](https://www.npmjs.com/package/neucron-sdk) to handle authentication, wallet management, and transaction handling securely and efficiently.

> 🔐 **Project by Team 5 (CyberGuard Innovations)**  
> ⚙️ Built with Bun + Node.js

---

## ⚙️ Pre-Requisites

Make sure the following tools are installed before running this project:

1. ✅ [**Bun**](https://bun.sh/docs/installation)  
2. ✅ [**Node.js**](https://nodejs.org/)

---

## 🚀 How to Run

Open your terminal in the root folder of this project and execute the following commands:

### ▶️ Main Function Execution

```bash
bun run nec-aut.js
```

This handles:

- ✅ Authentication (Sign Up/Login)
- ✅ Wallet management
- ✅ Transactions (send funds)
- ✅ Wallet creation and history lookup

---

### 🔐 Transaction Signing & WIF Conversion

```bash
bun run bsvdk.js
```

This file is responsible for:

- 🔑 Signing transactions securely  
- 🔁 Converting private keys to **WIF (Wallet Import Format)** — a standard used to represent and transfer private keys across wallets.

---

## 🧑‍💻 What It Does

Using `nec-aut.js`, you can:

- 🔐 Sign up or log in to Neucron-powered wallets
- 💼 Fetch wallet keys, balances, addresses
- 💸 Send transactions to any address
- 🧾 View wallet transaction history
- 🪙 Create a new wallet and fetch:
  - Balance
  - Addresses
  - Mnemonic
  - All UTXOs
  - Extended Public Keys (xPub)

---

## 💡 Sample Prompts

```
Do you want to sign up (s) or login (l)? 
Enter your wallet ID:
Enter transaction address:
Enter transaction note:
Enter transaction amount:
```

---

## 📂 Project Structure

```
cyberguard-cli/
├── nec-aut.js    # Main script for wallet & transaction logic
├── bsvdk.js      # Key signing & WIF conversion
├── package.json
└── README.md     # You're here!
```

---

## 🛠 Tech Stack

- [Neucron SDK](https://www.npmjs.com/package/neucron-sdk)
- [Bun Runtime](https://bun.sh/)
- Node.js
- ESModules & Readline interface

---

## 📣 Feedback Welcome!

We’re always looking to improve.  
Feel free to open an issue or pull request with suggestions!

---

## 🙌 Team

**Team 5 — CyberGuard Innovations**  
🔐 Building secure, privacy-focused CLI tools for modern blockchain environments.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

