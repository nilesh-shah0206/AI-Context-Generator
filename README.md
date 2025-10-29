<div align="center">

<img width="128" height="128" alt="superhero-dev" src="https://github.com/user-attachments/assets/c716fb81-27e3-4acf-a873-e6425a39e136" />

# AI-Context-Generator

</div>

**AI-Context-Generator** is a collection of advanced AI prompt chains. These prompts are designed to help AI agents like GitHub Copilot move beyond simple autocomplete and become valuable, context-aware teammates.

Each prompt or prompt chain is built to guide the AI through specific engineering workflows — analyzing a codebase, generating documentation, implementing features, and more — using clearly defined, repeatable steps that reflect how real engineers work.

Our goal is to bridge the gap between general-purpose AI models and project-specific knowledge, enabling faster, more accurate, and more scalable development.

## Repository Structure

Prompts in this repo are organized into **high-level categories** based on what they help the AI accomplish:

- **`/understanding-code`** – Prompt chains that help AI understand and document existing codebases

Each subfolder contains one or more prompts or prompt chains, each with its own `README.md` explaining how to use it.

## What's Inside

Here are a few currently available prompt chains:

### 1. Developer Docs Generator

**Path:** `understanding-code/instruction-generation`

Generates a `copilot-instruction.md` file that helps AI tools operate effectively within your codebase. Ideal for onboarding AI tools (or humans) with deep, structured context.

**Features:**

- Analyzes the tech stack and architecture
- Categorizes files by role
- Extracts coding patterns and naming conventions
- Documents features and domain logic

→ [View prompt chain](./understanding-code/instruction-generation/README.md)
