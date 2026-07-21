# Agentic-AI
Agentic AI Project
Simple Reflex Agent – Smart Room Cleaning Agent

simple-reflex-agent-smart-room-cleaner/
│
├── simple_reflex_agent.py
├── requirements.txt
├── README.md
└── .gitignore

Prerequisite:
Need to install python
#py --version
Need to present matplotlib
#py -m pip install matplotlib
then run the code 
#py demo_simple_reflex_agent.py

# 🤖 Simple Reflex Agent – Smart Room Cleaning Agent

## 📌 Project Overview

This project demonstrates a basic Artificial Intelligence concept called a **Simple Reflex Agent** using Python.

The agent operates in a simulated 2x2 room environment containing four rooms. Each room can be either:

- 🟢 Clean
- 🔴 Dirty

The agent observes the current state of the room and takes an action based on a predefined rule.

### Agent Behavior

- If the current room is **Dirty** → The agent performs the **Clean** action.
- If the current room is **Clean** → The agent performs the **Move** action and moves to the next room.

The environment is visually represented using **Matplotlib**, where:

- 🔴 Red = Dirty Room
- 🟢 Green = Clean Room
- 🔵 Blue Circle = AI Agent

The simulation runs for a fixed number of steps and displays the agent's movement and cleaning actions.

---

## 🎯 Project Objective

The main objective of this project is to understand the basic working principles of an AI Agent.

The agent follows a simple perception-action cycle:

```text
Observe → Decide → Act → Move → Observe Again


