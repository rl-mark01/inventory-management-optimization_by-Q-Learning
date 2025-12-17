# 📦 Inventory Management Optimization using Q-Learning

## 📌 Project Overview
This project applies **Q-Learning (Reinforcement Learning)** to a simplified
warehouse inventory management problem.  
The objective is to learn an optimal policy that balances **restocking, selling,
and holding inventory** under uncertain demand and price conditions.

Rather than relying on fixed rules, the agent learns decision-making strategies
through interaction with a custom environment.

---

## 🧠 Problem Definition
Inventory management involves trade-offs between:
- Stockouts (lost sales due to no inventory)
- Overstocking (excess holding costs)
- Uncertain demand and price fluctuations

This project models the problem as a **Markov Decision Process (MDP)** and solves
it using tabular Q-Learning.

---

## 🏗️ Environment Design
A custom Gymnasium environment (`WarehouseEnv`) is implemented with:

### 🔹 State Space
- Inventory level: 0–100
- Demand level: 0–9
- Price level: 5 discrete levels  

State representation:
