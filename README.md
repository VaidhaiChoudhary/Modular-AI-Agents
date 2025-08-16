# Modular AI Agents – LangChain + Groq

Instead of relying on one big, all-in-one model, **modular AI agents** are built from specialized components (like memory, code execution, search, or summarization), each focused on a specific skill. A central controller or planner breaks down complex tasks and intelligently delegates work across these modules—making the system more flexible, task-aware, and adaptable. This approach enables agents to reason, plan, and execute using the right tool for each step, greatly improving scalability and extensibility.

This **project** demonstrates a **modular AI agent** using LangChain and Groq’s LLaMA3 model.  

The agent can intelligently **orchestrate tasks across multiple tools** such as:

- **Wikipedia API** – for factual lookups  
- **Custom Calculator** – for evaluating math expressions  

The LLM (LLaMA3 via Groq) acts as the **orchestrator**: it decides which tool to use for each part of a user query, executes the tools, and combines the results.  

### Technologies Used
- LangChain (agents, tools)
- LangChain-Community (Wikipedia wrapper)
- Groq API + langchain-groq (LLaMA3 model)
- Python (custom calculator tool)

This notebook provides a simple working example of **agentic AI orchestration**, showing how multiple specialized modules can be combined into a single workflow.
