# Binance Trading Bot 🪙🤖

A Python-based crypto trading bot that interacts with the **Binance Futures Testnet** API.  
This bot allows users to simulate **market** and **limit** orders using custom input, without executing real trades — perfect for learning and testing.

---

## 📌 Features

- ⚙️ Connects to Binance Futures **Testnet**
- 🧠 Simple simulation of trading orders (`buy`/`sell`)
- 🔒 Uses your own Testnet **API Key** and **Secret**
- 📄 Logs all actions to a file (`trading_bot.log`)
- 🔁 Supports both **MARKET** and **LIMIT** orders
- ✅ Avoids real trading – safe for demo and portfolio



## 🚀 Project Structure
```
binance-trading-bot/
├── trading_bot.ipynb # Main Jupyter Notebook (interface + logic)
├── trading_bot.log # Log file for tracking actions
├── README.md # This file
```


## 📥 Requirements

Install the required package:

```bash
pip install python-binance
```

## 🛠️ How to Use

1. **Get Binance Testnet API Keys**
   - Go to [Binance Futures Testnet](https://testnet.binancefuture.com/)
   - Create an account and generate your API Key and Secret

2. **Run the Notebook**
   - Open `trading_bot.ipynb` in Jupyter Notebook
   - When prompted, enter:
     - ✅ API Key  
     - ✅ API Secret  
     - ✅ Trading pair (e.g., `BTCUSDT`)  
     - ✅ Order side (`buy` or `sell`)  
     - ✅ Order type (`MARKET` or `LIMIT`)  
     - ✅ Quantity  
     - ✅ Limit price (if using a LIMIT order)

3. **Check Logs**
   - All simulated orders will be logged in `trading_bot.log`

⚠️ Disclaimer
This project uses the Binance Futures Testnet and simulates trading.
It does not place real orders and is intended strictly for educational purposes.


---

### ✅ Now to apply this:
1. Paste the above content into your `README.md` file.
2. Then run:

```bash
git add README.md
git commit -m "Cleaned and formatted final README.md"
git push origin main

