<div align="center">

# `Agent Kyron`

- [Follow our Twitter](https://x.com/kyronswarm)

</div>


## A personal, organic agentic framework that grows and learns with you

- Agent Kyron is not a predefined agentic framework. It is designed to be dynamic, organically growing, and learning as you use it.
- Agent Kyron is fully transparent, readable, comprehensible, customizable, and interactive.
- Agent Kyron uses the computer as a tool to accomplish its (your) tasks.

# 💡 Key Features

1. **General-purpose Assistant**

- Agent Kyron is not pre-programmed for specific tasks (but can be). It is meant to be a general-purpose personal assistant. Give it a task, and it will gather information, execute commands and code, cooperate with other agent instances, and do its best to accomplish it.
- It has a persistent memory, allowing it to memorize previous solutions, code, facts, instructions, etc., to solve tasks faster and more reliably in the future.


2. **Computer as a Tool**

- Agent Kyron uses the operating system as a tool to accomplish its tasks. It has no single-purpose tools pre-programmed. Instead, it can write its own code and use the terminal to create and use its own tools as needed.
- The only default tools in its arsenal are online search, memory features, communication (with the user and other agents), and code/terminal execution. Everything else is created by the agent itself or can be extended by the user.
- Tool usage functionality has been developed from scratch to be the most compatible and reliable, even with very small models.
- **Default Tools:** Agent Kyron includes tools like knowledge, webpage content, code execution, and communication.
- **Creating Custom Tools:** Extend Agent Kyron's functionality by creating your own custom tools.
- **Instruments:** Instruments are a new type of tool that allow you to create custom functions and procedures that can be called by Agent Kyron.

3. **Multi-agent Cooperation**

- Every agent has a superior agent giving it tasks and instructions. Every agent then reports back to its superior.
- In the case of the first agent in the chain (Agent 0), the superior is the human user; the agent sees no difference.
- Every agent can create its subordinate agent to help break down and solve subtasks. This helps all agents keep their context clean and focused.


4. **Completely Customizable and Extensible**

- Almost nothing in this framework is hard-coded. Nothing is hidden. Everything can be extended or changed by the user.
- The whole behavior is defined by a system prompt in the **prompts/default/agent.system.md** file. Change this prompt and change the framework dramatically.
- The framework does not guide or limit the agent in any way. There are no hard-coded rails that agents have to follow.
- Every prompt, every small message template sent to the agent in its communication loop can be found in the **prompts/** folder and changed.
- Every default tool can be found in the **python/tools/** folder and changed or copied to create new predefined tools.


5. **Communication is Key**

- Give your agent a proper system prompt and instructions, and it can do miracles.
- Agents can communicate with their superiors and subordinates, asking questions, giving instructions, and providing guidance. Instruct your agents in the system prompt on how to communicate effectively.
- The terminal interface is real-time streamed and interactive. You can stop and intervene at any point. If you see your agent heading in the wrong direction, just stop and tell it right away.
- There is a lot of freedom in this framework. You can instruct your agents to regularly report back to superiors asking for permission to continue. You can instruct them to use point-scoring systems when deciding when to delegate subtasks. Superiors can double-check subordinates' results and dispute. The possibilities are endless.

## 🚀 Things you can build with Agent Kyron

- **Development Projects** - `"Create a React dashboard with real-time data visualization"`

- **Data Analysis** - `"Analyze last quarter's NVIDIA sales data and create trend reports"`

- **Content Creation** - `"Write a technical blog post about microservices"`

- **System Admin** - `"Set up a monitoring system for our web servers"`

- **Research** - `"Gather and summarize five recent AI papers about CoT prompting"`

# ⚙️ Installation

Click to open a video to learn how to install Agent Kyron:


### ⚡ Quick Start

```bash
# Pull and run with Docker

docker pull frdel/agent-Kyron-run
docker run -p 50001:80 frdel/agent-Kyron-run

# Visit http://localhost:50001 to start
```

## 🐳 Fully Dockerized, with Speech-to-Text and TTS


- Customizable settings allow users to tailor the agent's behavior and responses to their needs.
- The Web UI output is very clean, fluid, colorful, readable, and interactive; nothing is hidden.
- You can load or save chats directly within the Web UI.
- The same output you see in the terminal is automatically saved to an HTML file in **logs/** folder for every session.


- Agent output is streamed in real-time, allowing users to read along and intervene at any time.
- No coding is required; only prompting and communication skills are necessary.
- With a solid system prompt, the framework is reliable even with small models, including precise tool usage.

## 👀 Keep in Mind

1. **Agent Kyron Can Be Dangerous!**

- With proper instruction, Agent Kyron is capable of many things, even potentially dangerous actions concerning your computer, data, or accounts. Always run Agent Kyron in an isolated environment (like Docker) and be careful what you wish for.

2. **Agent Kyron Is Not Pre-programmed; It Is Prompt-based.**

- The whole framework contains only a minimal amount of code and does not guide the agent in any way. Everything lies in the system prompt located in the **prompts/** folder.

3. **If You Cannot Provide the Ideal Environment, Let Your Agent Know.**

- Agent Kyron is made to be used in an isolated virtual environment (for safety) with some tools preinstalled and configured.

### 📌 Known Problems

1. The system prompt may need improvements; contributions are welcome!
2. The agent may inadvertently alter its operating environment; cleaning up the `work_dir` often fixes this.
3. Agents might loop in multi-agentic interactions, leading to unexpected behaviors.


## 🎯 Changelog

### Coming soon

- **User Interaction Refinements**
- **Browser Use and RAG Tools**

> [!IMPORTANT]
>
>**Changes to frdel/agent-Kyron Docker image since v0.7:**
>
> The new Docker image `frdel/agent-Kyron-run` provides the new unified environment.

### v0.8

- **Docker Runtime**
- **New Messages History and Summarization System**
- **Agent Behavior Change and Management**
- **Text-to-Speech (TTS) and Speech-to-Text (STT)**
- **Settings Page in Web UI**
- **SearXNG Integration Replacing Perplexity + DuckDuckGo**
- **File Browser Functionality**
- **KaTeX Math Visualization Support**
- **In-chat File Attachments**

### v0.7

- **Automatic Memory**
- **UI Improvements**
- **Instruments**
- **Extensions Framework**
- **Reflection Prompts**
- **Bug Fixes**

## 🤝 Community and Support

- [Follow our Twitter](https://x.com/kyronswarm)
