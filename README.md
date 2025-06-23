# 🚀 EVE Online RL Agent  
*A Reinforcement Learning agent in a custom simulation inspired by the EVE Online universe*

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Enabled-red?logo=pytorch)](https://pytorch.org/)
[![Reinforcement Learning](https://img.shields.io/badge/Reinforcement--Learning-DQN-brightgreen)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🧠 Overview

This project implements a **Deep Q-Network (DQN)** agent to navigate a simulated economic environment inspired by **EVE Online**. The agent autonomously:

- Mines asteroids
- Manages fuel and energy
- Sells minerals at stations
- Refuels and plans routes

The environment is entirely custom-built using `pygame` and `gymnasium`, allowing the agent to learn economic and strategic behavior in a dynamic and visually interactive space. We've also written a NeurIPS style paper to summarize our findings.

---

## 🎯 Objectives

- Design a simulation of EVE Online's resource-based mining ecosystem
- Train a DQN agent to optimize mining and trading strategies
- Visualize and compare learned policy vs. rule-based behavior
- Demonstrate reinforcement learning in a real-time visual environment

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **PyTorch** – deep learning and DQN implementation
- **Gymnasium** – environment framework
- **Pygame** – real-time 2D rendering of agent behavior
- **Matplotlib** – visualization of metrics
- **Numpy** – numerical logic and environment backend

---

## 📁 Project Structure

```bash
eve-online-RL-agent/
├── dqn_agent.py          # DQN agent training and evaluation loop
├── dqn_env.py            # DQN-compatible gym-style environment
├── environments.py       # Simulation backend and reward mechanics
├── ppo_env.py            # Alternate PPO-style env interface
├── simple_agent.py       # Rule-based heuristic agent
├── main.py               # Entry point for simulation visualization
├── dqn_agent.pth         # Saved PyTorch model weights
