🧠 AI Agent Learning Series

This repo is a hands-on exploration of AI agent design, tool integration, and multi-agent collaboration. It starts with simple LLM-based tools and builds toward more robust, modular, and reliable agent systems—focusing on clarity, safety, and reusability.

📦 Structure

The notebook series is organized into progressive chapters:

01.00 Series – Foundations
- 01.01_SETUP: Environment setup and base configuration
- 01.02_DumbCustomerServiceAgent: Minimal working agent with hardcoded logic
- 01.03_My First Agent_File Reader: First tool-using agent with file input
- 01.04_File Reader with LLM Function Calling: Adds structured output via OpenAI function calls
- 01.05_File Reader with Agent Loop: Introduces reasoning/action loop pattern
- 01.06_GAME Framework: Formalizes agent behavior using a Goal–Action–Memory–Evaluation loop
- 01.07_ToolDecorators: Decorator pattern for tool abstraction and reusability
- 01.08_Inventory Management Agent: WIP practical use case using tools and memory

02.00 Series – Intermediate Systems & Patterns
- 02.01_Flexible vs Reliable Invoice Reader: Tradeoffs in parsing robustness vs flexibility
- 02.02_Invoice Processing Agent: End-to-end invoice parsing with tools
- 02.03_Persona Patterns: Static vs dynamic prompting strategies
- 02.04_Invoice Agent with Experts: Role-based decomposition of tasks using multiple specialized agents
- 02.05_Environmental Safety: Preventing runaway loops, hallucinations, and unsafe tool usage
- 02.06_Multi-Agent Systems: Coordination among agents with distinct capabilities
- 02.07_Clean AI Tools: Uses dependency injection and clean tool interfaces
- 02.08_Agent Capabilities: Formalizing skills and affordances in agent design
- 02.09_Plan First Capability: Planning-first pattern to improve multi-step task handling

🧩 Key Concepts Covered
- 🛠 Tool abstraction (including decorators)
- 🔁 Agent loops (e.g. ReAct, GAME)
- ⚠️ Safe agent execution (timeouts, limits)
- 🧠 Multi-agent collaboration
- 🧪 Dependency injection for AI tools
- 👤 Prompting strategies (personas, static/dynamic chaining)

📌 Why This Matters

As LLM-based agents get deployed in real-world systems, robustness, modularity, and interpretability matter. This repo serves as a practical guide for designing agents that are not only functional but maintainable and safe.

📄 Requirements
- Python 3.10+
- openai, langchain, pydantic, tqdm, and other common agent libraries
- An OpenAI API key stored in .env or directly in the notebook
