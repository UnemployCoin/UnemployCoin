# UnemployCoin (UNEMP)

**UnemployCoin (UNEMP)** is a decentralized ERC-20 token designed to support community initiatives, especially aimed at assisting the unemployed. The token contract follows best practices in smart contract design, emphasizing transparency, security, and administrative control when needed.

---

## 🔍 Overview

This smart contract implements a standard ERC-20 token with added **Ownable** and **Pausable** features:

- ✅ **Minted Supply:** 1,000,000,000 UNEMP tokens minted to the deployer's address upon deployment.
- 🔐 **Ownership Control:** The deployer becomes the owner and can transfer or renounce ownership.
- ⏸️ **Pausable Functionality:** The owner can pause/unpause all token transfers for emergency or upgrade scenarios.
- 🔄 **ERC-20 Compliance:** Implements standard ERC-20 functions and events for compatibility and integration.

---

## ⚙️ Features

- 🔁 **Standard ERC-20 Methods**
  - `transfer`, `approve`, `transferFrom`, `balanceOf`, `totalSupply`
- 🧾 **Ownable**
  - Only the contract owner can call sensitive admin functions.
- 🚨 **Pausable**
  - All transfers are halted when paused, resumed only by the owner.
- 🔐 **Secure Internal Logic**
  - Includes basic transfer and allowance checks to comply with ERC-20 expectations.

---

## 🧑‍💻 Technical Details

- **Token Name:** UnemployCoin  
- **Symbol:** UNEMP  
- **Decimals:** 18  
- **Initial Supply:** 1,000,000,000 UNEMP  
- **Network:** Polygon (EVM Compatible)  
- **Contract Address:** `0xe1e64a89C7B95F23C601943147228784CCA35395`  
- **License:** MIT  
- **Solidity Version:** ^0.8.0 (EVM: Cancun)

---

## 🧠 Author

**Chris Williams**  
Deployed: June 4, 2025  
Twitter: [@UnemployCoin](https://twitter.com/UnemployCoin)

---

## 🌐 Community & Links

- 🌍 Website:  [UnemployCoin.com](https://UnemployCoin.com)
- 🐦 Twitter: [@UnemployCoin](https://twitter.com/UnemployCoin)  
- 📜 Contract Source: [PolygonScan](https://polygonscan.com/address/0xe1e64a89C7B95F23C601943147228784CCA35395)  
- 🛠 GitHub: [UnemployCoin.io Repository](https://github.com/UnemployCoin/unemploycoin.github.io)

---

## 🛡 Security Notes

This contract follows Solidity security best practices, but it is **not audited**. Use at your own risk. Recommended future improvements include:

- Integrating SafeMath (optional in >=0.8.0 but helps auditability).
- Enhanced input validation and protection against approval race conditions.
- Automated testing and formal verification tools.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

