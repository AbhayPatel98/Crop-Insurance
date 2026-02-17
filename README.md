#  Crop Insurance Smart Contract

Decentralised **Crop Insurance Protocol** built on Solidity to automate insurance payouts for farmers based on predefined risk conditions.

This project demonstrates blockchain use cases in **agriculture insurance**, combining smart contracts with real-world parameters (e.g., weather conditions, risk triggers, oracles).

---

## Project Summary

Crop Insurance is a Solidity-based smart contract that:

✔ Allows farmers to purchase insurance  
✔ Tracks risk conditions (oracle or simulated)  
✔ Automates payout on verified conditions  
✔ Enables insurer underwriting logic

This project serves as a **proof-of-concept for decentralized insurance logic**.

---

##  Features

- Policy purchase & premium storage  
- Risk condition simulation  
- Claim request & verification  
- Payout distribution


Core functionalities:

| Function | Purpose |
|----------|---------|
| `buyPolicy()` | Farmer pays premium and registers policy |
| `requestClaim()` | Farmer requests claim based on conditions |
| `verifyClaim()` | Admin/oracle verifies risk condition |
| `payout()` | Sends payout if verified |

---

## 🧠 Design Concepts

### 🔍 Underwriting Logic
Risk is verified through oracle or admin function — replaceable for real oracle integrations.

### 🔑 Roles
- **Farmer:** Buys policies
- **Insurer/Admin:** Verifies claims
- **Oracle (optional):** Provides external condition data

---

## 🛠️ Stack & Tools

✔ Solidity 0.8.x  
✔ Foundry (for tests)  
✔ Hardhat (optional)  
✔ JavaScript testing

---

## 🚀 Setup & Installation

Clone the repo:

```bash
git clone https://github.com/AbhayPatel98/Crop-Insurance.git
cd Crop-Insurance

---

## Smart Contract

Located at:



Core functionalities:

| Function | Purpose |
|----------|---------|
| `buyPolicy()` | Farmer pays premium and registers policy |
| `requestClaim()` | Farmer requests claim based on conditions |
| `verifyClaim()` | Admin/oracle verifies risk condition |
| `payout()` | Sends payout if verified |

---

##  Design Concepts

### Underwriting Logic
Risk is verified through Oracle or admin function — replaceable for real Oracle integrations.

###  Roles
- **Farmer:** Buys policies
- **Insurer/Admin:** Verifies claims
- **Oracle (optional):** Provides external condition data

---

## Stack & Tools

✔ Solidity 0.8.x  
✔ Foundry (for tests)  
✔ Hardhat (optional)  
✔ JavaScript testing

---

## Setup & Installation

Clone the repo:

```bash
git clone https://github.com/AbhayPatel98/Crop-Insurance.git
cd Crop-Insurance

