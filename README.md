# Quant Battlegrounds ⚔️📈

**Quant Battlegrounds** is a tiny Python playground for aspiring quants to battle-test simple trading ideas on a price series – entries, exits, inventory, P&L, the whole lot.

It’s **intentionally imperfect**.

Inside the notebook you’ll find:

- A very simple baseline strategy you can tweak in a few lines  
- Basic features + backtest logic you’re encouraged to tear apart  
- Inventory, value and P&L plots to visualise behaviour over time  
- A clear **look-ahead bias** baked in on purpose  
- An updated version with a simple **`buy` / `sell` status** to control the next action and sharpen the execution logic

The point isn’t to ship a production-ready backtester.  
The point is to show how fragile a backtest becomes when you ignore:

- inventory control  
- execution state (what you’re *allowed* to do next)  
- data leakage / look-ahead bias  
- transaction costs and slippage  

---

## Your challenge

If you’re an aspiring quant, use this repo as a small “training ground”:

1. **Develop your Strategy!**
2. **Advance** the inventory framework
3. **Remove** the look-ahead bias  
4. **Add** transaction costs and slippage  
5. **Beat** the baseline strategy in a clean backtest  
6. (Optional) Experiment with your own features, entry/exit rules or execution layer

If you build something interesting – new features, better execution rules, or a totally different strategy – feel free to open a PR or tag me on LinkedIn.

---

## Getting started

1. Clone the repo:
   ```bash
   git clone https://github.com/TomorrowCapitalResearch/Quant-Battlegrounds.git
   cd Quant-Battlegrounds
