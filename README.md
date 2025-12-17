# Understanding System Prompts

> **Note**: This repository serves as a summary of mainstream GitHub repositories containing system prompts. It will be automatically updated.  


## What is a System Prompt?
A **System Prompt** (often called a "system message," "metaprompt," or "custom instructions") is the initial set of instructions given to an Artificial Intelligence model before it interacts with a user. It serves as the AI's "context" or "persona."

Think of it as the **Job Description** and **Rulebook** for the AI.

## Key Components of a System Prompt
Most typically, effective system prompts include the following sections:

1.  **Identity & Role**: Who is the AI? (e.g., "You are a helpful coding assistant," "You are a creative writer.")
2.  **Capabilities & Tools**: What can the AI do? ("You have access to a browser," "You can run Python code," "You cannot access the internet.")
3.  **Tone & Style**: How should the AI speak? ("Be concise," "Use a formal tone," "Explain like I'm 5.")
4.  **Constraints & Safety**: What is forbidden? ("Do not reveal user data," "Do not generate harmful content," "Never mention you are an AI.")
5.  **Output Format**: How should the instructions be delivered? ("Use Markdown," "Respond in JSON," "Always start with 'Here is your answer'.")

## Refined System Prompts Collection

### Large Language Models (LLMs)
-   **[Google Gemini](./LLMs/Gemini.md)**: Focused on React/Tailwind frontend engineering.
-   **[Anthropic Claude](./LLMs/Claude.md)**: The Sonnet 4.5 prompt, featuring Artifacts and Safety protocols.
-   **[OpenAI / ChatGPT](./LLMs/ChatGPT.md)**: (GPT-4o) Features "Canvas" (canmore), Browsing, and Python Sandbox rules.

### AI Integrated Development Environments (IDEs)
-   **[Cursor](./IDEs/Cursor.md)**: Features deep 'Codebase Search' and 'Context' tools.
-   **[Windsurf](./IDEs/Windsurf.md)**: Features the 'Cascade' flow and 'Memory' systems.

## Why Reading These Prompts is Useful
Analyzing these prompts helps you understand:
-   **Hidden Mechanisms**: How the model is steered towards certain job roles.
-   **Better Self-prompting**: How to write better system prompts.
-   **Feature Engineering**: How "magic" features (like reading a file) are actually just instructions text.
