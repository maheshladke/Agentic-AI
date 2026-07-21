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
1- Project- Simple Reflex Agent 
"I developed a Simple Reflex Agent using Python to understand the fundamental concepts of AI agents. I created a simulated 2x2 room environment where each room can be clean or dirty. The agent observes the current state of the room and uses a predefined condition-action rule. If the room is dirty, the agent cleans it. If the room is clean, the agent moves to the next room. I used Matplotlib to visualize the environment and agent movement. This project helped me understand the basic agent architecture of perception, decision-making, and action, which forms the foundation for more advanced agentic AI systems."

2- Project -Goal-Based Smart Room Cleaning Agent.
"My second project is a Goal-Based Smart Room Cleaning Agent. I developed it to understand how an AI agent can work toward a predefined goal rather than simply reacting to the current environment. The goal of the agent is to make all rooms clean. The agent continuously observes the environment, checks the current room state, performs cleaning when necessary, and moves between rooms. The agent evaluates whether the overall goal has been achieved and terminates the simulation once all rooms are clean. This project helped me understand goal-based decision-making and the difference between reactive and goal-oriented agents."

3- Project-Utility-Based Smart Cleaning Agent

"My third Agentic AI project is a Utility-Based Smart Cleaning Agent. I extended my previous Goal-Based Agent by introducing a utility mechanism. The agent's goal is still to clean all rooms, but now it also considers the cost associated with different actions. I assigned costs to cleaning and movement and designed the agent to select actions based on their utility. This helped me understand how utility-based agents optimize decisions rather than simply achieving a goal. The key difference is that a goal-based agent focuses on whether the goal can be achieved, while a utility-based agent also evaluates the quality and efficiency of different possible actions."


