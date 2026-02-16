# Advanced-LLM-Agents-and-Interpretability.

Advanced LLM Agents & Mechanistic Interpretability 🤖🧠
This repository showcases advanced techniques in Large Language Model (LLM) engineering. It covers the end-to-end lifecycle of building autonomous AI agents and looking "under the hood" of transformer models to understand their decision-making processes.

🏗️ Core Modules
1. Autonomous AI Agents (/ai-agents)
MATE Design Principles: Implemented AI agents adhering to the MATE framework—focusing on Model efficiency, Action specificity, Token efficiency, and Environmental safety.

Automated Invoice Processing: Built a fully optimized agent capable of ingesting raw text and multiple document formats to extract structured financial data (e.g., Vendor, Line Items, Totals).

2. LLM Customization & X-Ray (/llm-engineering)
API-Based Fine-Tuning: Developed a pipeline to format data into JSONL and fine-tune OpenAI's GPT models via their API to improve task-specific performance.

Mechanistic Interpretability: Utilized TransformerLens to "X-ray" LLMs. This involves inspecting internal circuit activations, tracking induction loss over training tokens, and manipulating internal model states to understand how transformers write and process text.

🛠️ Tech Stack
Agent Frameworks: Custom prompt engineering, JSON structured outputs.

Interpretability: TransformerLens, Circuitviz.

APIs: OpenAI SDK.

File System Agent: Built an LLM agent with Function Calling capabilities to autonomously navigate directories, list files, and read content.

Data Governance Agent: Designed an AI auditor that autonomously flags datasets for class imbalance, privacy risks, and bias.
