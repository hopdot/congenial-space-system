
---

## 🔑 Features

1. **MetaMask Authentication**
   - Frontend requests a **nonce** from backend.
   - User signs with MetaMask.
   - Backend verifies signature using `ethers.js`.

2. **Trading Signals**
   - Fetches price history (via CoinGecko API).
   - Calculates **RSI(14)** & **MACD(12,26,9)**.
   - Blends with **strategy.json** model for signals (`buy` / `sell` / `hold`).

3. **Deploy Anywhere**
   - **Frontend**: GitHub Pages (auto-published to `/HCX/` repo).  
   - **Backend**: Render / Vercel with GitHub Actions workflows.

---

## ⚙️ Setup

### 1. Clone repo
```sh
git clone https://github.com/howeecross/HCX.git
cd HCX
