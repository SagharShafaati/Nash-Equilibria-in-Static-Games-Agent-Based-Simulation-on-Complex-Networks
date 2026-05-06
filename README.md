# Nash Equilibria in Static Games: Agent-Based Simulation on Complex Networks

This project simulates the evolution of strategies in 2-player static games using **agent-based modeling** on various types of **complex networks**. It explores how **network topology** and different **strategy update rules** influence the convergence toward **Nash equilibria**.

---

## 📌 Objectives

- Model **strategic behavior** of agents playing classic games (e.g., Prisoner's Dilemma) on networks.
- Examine how different **update mechanisms** (e.g., replicator dynamics, imitation) affect strategy evolution.
- Evaluate how **network types** (e.g., scale-free, small-world, community-based) influence the emergence and stability of **Nash equilibria**.

---

## 🧠 Core Concepts

- **Nash Equilibrium**: A state where no agent can improve its payoff by unilaterally changing strategy.
- **Agent-Based Modeling**: Each node in the network is an agent with an evolving strategy.
- **Evolutionary Game Theory**: Agents adapt strategies based on payoff-based learning or imitation.
- **Complex Networks**: Topologies used include:
  - Erdos-Renyi (random)
  - Barabasi-Albert (scale-free)
  - Watts-Strogatz (small-world)
  - Complete graph
  - Homogeneous (regular)
  - LFR benchmark (community-rich)

---

## 📂 Structure

### 🔧 Game Definitions
Classic 2-player games are defined using payoff matrices:
- Prisoner's Dilemma
- Hawk-Dove
- Stag Hunt
- Public Goods Game (function-based)

### 🌐 Network Generation
Creates networks using `networkx`, supporting:
- Random graphs
- Scale-free networks
- Small-world networks
- Modular/community-based graphs via LFR

### 🔁 Strategy Update Mechanisms
Implements various strategy dynamics:
- `Static`: No change in strategy
- `Replicator`: Strategies reproduced in proportion to payoffs
- `Unconditional Imitation`: Agents copy the highest earner
- `Moran`: Reproducer and replacer selected probabilistically
- `Fermi Rule`: Random comparisons with payoff-based imitation

---

## 📊 Metrics & Analysis (Expected / To Be Expanded)

- **Proportion of strategies** over time
- **Average payoff** and system-wide fitness
- **Community cohesion** and internal/external cooperation
- **Nash Equilibrium detection** (by verifying strategy stability)
- **Convergence patterns** (e.g., consensus, coexistence, oscillation)

---

## 🖼️ Visualization

Plots include:
- Evolution of strategy proportions
- Network diagrams showing agent strategies
- Community-based heatmaps
- Stability over time

---

## 📦 Requirements

Install required Python packages:

```bash
pip install numpy pandas networkx matplotlib seaborn



////

📌📌📌

⭐️ Influence of complex network topologies on nash equilibria in static games under dynamic simulations ⭐️
Volume 82, article number 397, (2026)
05 My 2026

Cite this article 
Shafaati, S., Azimi, M., Mohammadzadeh, J. et al. Influence of complex network topologies on nash equilibria in static games under dynamic simulations. J Supercomput 82, 397 (2026). https://doi.org/10.1007/s11227-026-08421-9

DOI:https://doi.org/10.1007/s11227-026-08421-9

Full version: https://rdcu.be/fg6oG 


