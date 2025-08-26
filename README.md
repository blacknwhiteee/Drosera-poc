# 🚀 ETH Large Transfer Trap

A custom **Drosera Trap** that monitors Ethereum Mainnet for transactions larger than **2 ETH**.  
When triggered, it logs the event and sends an alert to **Discord**.

---

## ⚡ Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/YOURNAME/eth-large-transfer-trap.git
   cd eth-large-transfer-trap
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run locally:
   ```bash
   drosera run
   ```

4. Deploy to Drosera Network:
   ```bash
   drosera deploy
   ```

---

## ✅ Features
- Detects large ETH transfers (above **2 ETH**)  
- Logs details with sender, receiver, and amount  
- Sends instant alert to **Discord**  

---

### Example Output
```
🚀 Big Transfer: 0xAAA... → 0xBBB... | 3.1420 ETH
🔥 Alert: 3.1420 ETH sent from 0xAAA... to 0xBBB...
```
