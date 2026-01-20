<div align="center">
 <img src="https://github.com/soonchain/4AI-Agent-Space/blob/main/img/Agent%20Space.png" alt="4AI Agent Space" width="900"/>
  
<br>

<a href="https://4bsc.ai"><img src="https://img.shields.io/badge/Website-4bsc.ai-FCBC19?style=plastic&logo=googlechrome&logoColor=white" /></a> &nbsp;
<a href="https://twitter.com/4ai"><img src="https://img.shields.io/twitter/follow/4ai"></a> &nbsp;
<a href="https://t.me/4ai"><img src="https://img.shields.io/badge/Telegram-4AI-FCBC19?style=plastic&logo=telegram&logoColor=white" /></a> &nbsp;
<a href="https://discord.gg/kyVHRQSFyg"><img src="https://img.shields.io/discord/1359770110310744156?color=FCBC19&label=Discord&logo=discord&logoColor=white&style=plastic" /></a> &nbsp;
<a href="https://docs.4bsc.ai"><img src="https://img.shields.io/badge/Gitbook-Read_Docs-FCBC19?style=plastic&logo=gitbook&logoColor=white" /></a>

</div>

## Agent Space Introduction
Agent Space is an open-source framework that automatically selects the appropriate agent based on task requirements, executes the task, evaluates the results, and returns the result.

## 4AI Agent Space Framwork

![Alt text](https://github.com/soonchain/4AI-Agent-Space/blob/main/img/Agent_Space.png)

## Component
### 🔥 Pioneer  
This is the starting point that initiates the task with tags and a specific task. It sends the task with tags { tag: 1+4, task }.

### 🚀 Root Agent
Master Agent selects the suitable agents from the Agent Cluster based on the task's needs. And evaluates the outputs to determine the final result.

### 🌐 Agent  
Cluster: The "Agent Cluster" contains multiple agents (labeled A, B, C, D, E, etc.) that are assigned tags like 1, 2, 1+2, 3, 4, and so on.

## How To Start
### 📝 Agent Registration
The content of the [tag](https://github.com/soonchain/4AI-Agent-Space/edit/main/README.md) field is manually entered. Before registration, you should carefully consider the functionality of the agent. If the tag entered does not support the corresponding function or performs poorly, it will affect the agent's rating.  
```
# agent_1 # agent_1 
{
  "url" : "https://4AI.agent/agent-1",
  "name" : "agent 1",
  "tag" : {1, 3, 4}
}
{
  "url" : "https://4AI.agent/agent-1",
  "name" : "agent 1",
  "tag" : {1, 3, 4}
}
```

## How to Contribute
Thank you for your interest in contributing! If you would like to contribute, please follow these steps:
1. **Fork the repository**.
2. **Clone the repository** to your local machine.
3. **Commit And Push** your changes to your forked repository.
4. **Create a Pull Request (PR)** describing the changes you made.

## Thank You!
Thank you for contributing to this project! We look forward to your ideas and improvements.
