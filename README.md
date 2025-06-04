# Nifty50 Virtual Portfolio Web App

---

## Tech Stack Used

- **Gradio**: To build an interactive, multi tab web UI.
- **YFinance**: Fetches real time stock data and historical prices.
- **Pandas & NumPy**: For data wrangling, signal processing, and portfolio calculations.
- **Python**: Core logic for signal generation, trade execution, and performance analytics.

---

## How the Project Works

### Stock Analyzer Tab
- Select a Nifty50 stock from the dropdown.
- Click "Analyze" to see:
  - **9 day Moving Average (MA9)**
  - **14 day RSI (Relative Strength Index)**
  - **Signal** (Buy/Sell/Hold) based on RSI & MA crossovers.

### Trade Tab
- Choose your stock and number of shares.
- Click **Buy** or **Sell**:
  - Capital is updated based on trade.
  - Each trade includes ₹20 commission.
  - Trades restricted by capital, min amount (₹1000), and position size (max 20%).

### Portfolio Tab
- Click **Refresh Portfolio** to view:
  - Holdings with Avg Buy Price, Current Price, P&L, and Days Held.
  - Best/Worst performing stock.
  - Portfolio Win Rate.
  - Total portfolio value (capital + stock value).

### Transactions Tab
- Click **Show Transactions** to see:
  - Date, Ticker, Buy/Sell, Quantity, Price, Commission, P&L, Notes.

---

## Instructions: How to Use the Website

1. **Launch the app**: Run the script (`python app.py` or use Jupyter/Colab).
2. **Navigate tabs**:
   - Start with **Stock Analyzer** to get trade signals.
   - Use **Trade** tab to simulate buys or sells.
   - Switch to **Portfolio** to monitor overall performance.
   - Review history in **Transactions** tab.
3. **Repeat**: Play around, simulate strategies, and watch your virtual capital grow!

---
