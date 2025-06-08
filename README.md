# UnemployCoin (UNEMP)

**UnemployCoin (UNEMP)** is a community-powered ERC-20 meme token with a real message: supporting the unemployed, the underdogs, and everyone left behind by the system. Built on the Polygon network with transparency, security, and purpose in mind, $UNEMP is more than just a meme — it’s a movement.

---

## 🔍 Overview

This smart contract implements a standard ERC-20 token, augmented with `Ownable` and `Pausable` extensions to allow emergency control while maintaining full compatibility with decentralized infrastructure.

### ✅ Token Specs
- **Total Supply:** 1,000,000,000 $UNEMP (Minted at deployment)
- **Token Name:** UnemployCoin
- **Symbol:** UNEMP
- **Decimals:** 18
- **Network:** Polygon (EVM Compatible)
- **Contract Address:** `0xe1e64a89C7B95F23C601943147228784CCA35395`

---

## ⚙️ Features

- 🔁 **ERC-20 Standard**  
  Full implementation of ERC-20 functions: `transfer`, `approve`, `transferFrom`, `balanceOf`, `totalSupply`.

- 🧾 **Ownable**  
  Administrative rights can be transferred or renounced. Only the owner can pause/unpause transfers.

- ⏸️ **Pausable**  
  Emergency pause functionality to freeze all token transfers — useful for contract upgrades or exploits.

- 🔐 **Security-Conscious Design**  
  Follows Solidity 0.8+ standards with overflow protections, basic allowance safety, and transfer integrity.

---

## 🧠 Project Vision

UnemployCoin was created not to make millionaires, but to give a voice to the forgotten — people ghosted by job apps, overlooked by systems, and sick of fake promises in crypto. It's a simple but bold message: **we deserve better**.

This project:
- Has **no fake roadmaps**, only real intentions.
- Emphasizes **transparency over hype**.
- Welcomes contributors and builders from all backgrounds.

---

## 🌐 Community & Links

- 🌍 Website: [https://UnemployCoin.com](https://UnemployCoin.com)
- 🐦 Twitter/X: [@UnemployCoin](https://twitter.com/UnemployCoin)
- 📜 Token Explorer: [PolygonScan](https://polygonscan.com/address/0xe1e64a89C7B95F23C601943147228784CCA35395)
- 🛠 GitHub: [UnemployCoin Repository](https://github.com/UnemployCoin/UnemployCoin)

---

## 🛡 Security Notes

While the contract follows security best practices, it has **not been formally audited**. It is deployed as-is, with the following recommendations for contributors:

- ✅ Consider SafeMath or OpenZeppelin libraries for enhanced audit readability.
- ✅ Add automated tests using Hardhat or Foundry.
- ✅ Review logic around `approve()` and race conditions.
- ✅ Verify contract ownership and pause control are safely managed.

---

## 📜 License

This project is licensed under the **MIT License** — free for anyone to use, build on, or fork, with credit.

---

## 🧑‍💻 Author

- **Chris Williams**
- Deployed: June 4, 2025
- Twitter: [@UnemployCoin](https://twitter.com/UnemployCoin)

---

> *“If this thing even helps one person feel seen, it was worth deploying.”*  
> – Chris
