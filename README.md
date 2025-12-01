# **🏠 SHAREY: A Multi-Agent Shared Housing Assistant**
*Meal Planning • Chore Coordination • Grocery Automation*

## **Project Overview**


### **Problem Statement** 
As young adults in new cities, we generally move into shared housing, needing to save costs. Sharing spaces gets exhausting when your housemates are NOT the best organizers or candidates for the 'first time living alone' experience.
So, how can we build a reliable intelligent system that helps housemates coordinate, track, and automate household chores, groceries, meal planning, and shared errands  in a fair, transparent, and easy way?

### **Solution**
SHAREY is a multi-agent AI system designed to help housemates coordinate and automate everyday shared-life tasks—meal planning, groceries, chores, and scheduling. Built using the Google/Kaggle Agent Development Kit (ADK), SHAREY demonstrates how specialized LLM-powered agents can collaborate to produce structured outputs and orchestrate household workflows.

The system includes three cooperating agents:

**1.  Meal Planner Agent:** 
 Generates weekly meal plans using a lightweight recipe “tool.”

**2. Grocery Manager Agent:** 
 Converts meal plans into ingredient lists and highlights missing items.

**3. Chore Scheduler Agent:** 
Suggests chore rotations based on the week's cooking plan and household roles.

A simple shared state allows the three agents to work sequentially:
Meal Plan → Grocery List → Chore Schedule.

This project demonstrates multiple key concepts from the Google/Kaggle course including multi-agent systems, custom tools, sequential orchestration, LLM-powered reasoning, state management, and agent deployment.

### **System Architecture**
1. User provides housemate names + dietary restrictions + week preferences
2. Meal Planner Agent generates structured plan referencing a local recipe file.
3. Grocery Manager parses the plan and produces a consolidated ingredient list.
4. Chore Scheduler distributes chores based on cooking assignments.
5. The system returns a final structured summary to the user.

### **Key Concepts**
a. Multi-agent system
b. Tools
c. Session & State Management

### **Running the agent**
Open the notebook and run the cells in order.

### **Results**
* Produces weekly meal plans using recipes
* Generates grocery list
* Assigns tasks to housemates.
