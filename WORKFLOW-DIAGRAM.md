```mermaid
%%{init: {'theme':'base', 'themeVariables': { 'primaryColor':'#4DD0E1','primaryTextColor':'#000','primaryBorderColor':'#0097A7','lineColor':'#757575','secondaryColor':'#ff8fab','tertiaryColor':'#7EE787'}}}%%
graph TD
    startAgentflow_0([🚀 Start])
    style startAgentflow_0 fill:#7EE787,stroke:#333,stroke-width:2px
    conditionAgentAgentflow_0{&🎯 Intent Router&#}
    style conditionAgentAgentflow_0 fill:#ff8fab,stroke:#333,stroke-width:2px
    agentAgentflow_1[🤖 Agent.Express]
    style agentAgentflow_1 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_2[🤖 Agent.Customs]
    style agentAgentflow_2 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_3[🤖 Agent.SupplyChain]
    style agentAgentflow_3 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_4[🤖 Agent.Freight]
    style agentAgentflow_4 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_5[🤖 Agent.CustomerService]
    style agentAgentflow_5 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_6[🤖 Agent.Technology]
    style agentAgentflow_6 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_7[🤖 Agent.Sustainability]
    style agentAgentflow_7 fill:#4DD0E1,stroke:#333,stroke-width:2px
    agentAgentflow_8[🤖 Agent.GlobalOps]
    style agentAgentflow_8 fill:#4DD0E1,stroke:#333,stroke-width:2px

    startAgentflow_0 --> conditionAgentAgentflow_0
    conditionAgentAgentflow_0 -->|S0| agentAgentflow_1
    conditionAgentAgentflow_0 -->|S1| agentAgentflow_2
    conditionAgentAgentflow_0 -->|S2| agentAgentflow_3
    conditionAgentAgentflow_0 -->|S3| agentAgentflow_4
    conditionAgentAgentflow_0 -->|S4| agentAgentflow_5
    conditionAgentAgentflow_0 -->|S5| agentAgentflow_6
    conditionAgentAgentflow_0 -->|S6| agentAgentflow_7
    conditionAgentAgentflow_0 -->|S7| agentAgentflow_8
```

![Nodes](https://img.shields.io/badge/Nodes-10-blue) ![Agents](https://img.shields.io/badge/Agents-8-green) ![Complexity](https://img.shields.io/badge/Complexity-Complex-orange) ![Memory](https://img.shields.io/badge/Memory-Enabled-purple) ![Tools](https://img.shields.io/badge/Tools-0-red)

---

**Total Nodes**: 10 | 
**Agents**: 8 | 
**Complexity**: Complex

<details>
<summary><b>🔍 View Agent Details (Click to Expand)</b></summary>

| Agent | Type | Description |
|-------|------|-------------|
| 🚀 Start | Start | Starting point of the agentflow |
| 🎯 Intent Router | ConditionAgent | Route user to appropriate agent based on detect... |
| 🤖 Agent.Express | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.Customs | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.SupplyChain | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.Freight | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.CustomerService | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.Technology | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.Sustainability | Agent | Dynamically choose and utilize tools during run... |
| 🤖 Agent.GlobalOps | Agent | Dynamically choose and utilize tools during run... |

</details>


### 🎨 Node Type Legend

| Icon | Type | Description |
|------|------|-------------|
| 🚀 | Start | Entry point of the workflow |
| 🤖 | Agent | AI agent with reasoning capabilities |
| 💬 | LLM | Large Language Model node |
| 🔀 | Condition | Branching logic |
| 🎯 | ConditionAgent | AI-powered conditional routing |
| 🔧 | Tool | External tool integration |
| ▶️ | ExecuteFlow | Execute another workflow |
| ⚙️ | CustomFunction | Custom JavaScript function |
| 🌐 | HTTP | HTTP request node |
| 👤 | HumanInput | Request human input/approval |
| 💭 | DirectReply | Direct message response |
| 🔄 | Loop | Loop back to previous node |
| 🔁 | Iteration | Iterate over array |
| 📝 | StickyNote | Documentation note |
