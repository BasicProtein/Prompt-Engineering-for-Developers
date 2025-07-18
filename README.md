<div align="center">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=FFC107" alt="Stars Badge"/>
  <img src="https://img.shields.io/github/forks/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=8BC34A" alt="Forks Badge"/>
  <img src="https://img.shields.io/github/contributors/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=03A9F4" alt="Contributors Badge"/>
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&color=f44336" alt="License Badge"/>
</div>

<h1 align="center">
  Awesome Developer Prompts
</h1>

<p align="center">
  An AI Prompt Engineering guide for developers. Curated, high-quality prompts covering the full SDLC: code generation, refactoring, debugging, testing & DevOps. Best practices for GPT-4, Gemini & Copilot to boost your coding efficiency.
</p>

<p align="center">
  <a href="./README.md"><strong>English</strong></a> | <a href="./README.zh-CN.md"><strong>中文</strong></a>
</p>

---

## 🚀 Why This Project?

In the era of Large Language Models (LLMs), developers have a powerful new partner. However, getting precise, production-ready, and robust responses from AI requires more than a simple question. Generic prompts often lead to generic, incomplete, or insecure code.

This repository is a curated collection of **prompt engineering patterns and best practices** specifically designed for software developers. Our goal is to help you turn your AI assistant from a simple code completer into a senior technical partner.

## ✨ Features

This guide provides systematically organized prompts for the entire software development lifecycle:

-   **💻 Code Generation & Refactoring:** Generate boilerplate, implement complex algorithms, and refactor legacy code with modern best practices.
-   **🐞 Debugging & Error Analysis:** Pinpoint root causes, interpret complex stack traces, and perform code reviews to find potential issues.
-   **✍️ API Design & Documentation:** Design RESTful/GraphQL schemas, auto-generate API docs, and create example payloads.
-   **🗃️ Database & SQL:** Write and optimize complex SQL queries, design database schemas, and generate ORM models.
-   **🧪 Test Case Generation:** Create unit tests, end-to-end (E2E) testing scripts, and cover critical edge cases.
-   **⚙️ DevOps & Automation:** Write CI/CD pipelines, generate Dockerfiles/K8s manifests, and craft automation scripts.
-   **🏛️ System & Architecture Design:** Compare technology choices and draft initial architecture design documents.

## 🔧 How to Use

The key to a great AI response is a great prompt. We recommend a structured approach for best results. A powerful prompt should include:

1.  **Persona (角色):** Assign a role to the AI (e.g., "You are a senior backend developer specializing in Python and performance optimization").
2.  **Context (上下文):** Provide all necessary background, including the programming language, frameworks, existing code, and the specific problem.
3.  **Task (任务):** Clearly define what you want the AI to do. Be specific and break down complex tasks.
4.  **Format (格式):** Specify the desired output format (e.g., "Provide the response in a single JSON file," "Use Markdown with code blocks for Python").

## 💡 Example: Refactoring a Python Function

Let's see the difference between a simple prompt and a structured prompt from this guide.

#### ❌ Simple Prompt

> "Refactor this python function"

This might give you a slightly better version, but it will likely miss crucial elements like error handling or documentation.

#### ✅ Structured Prompt (from this repository)

> **Persona:** You are a senior Python developer with expertise in writing robust, maintainable, and well-documented code.
>
> **Task:** Refactor the following Python function. Your refactoring must achieve these goals:
> 1.  Add comprehensive error handling for potential `ZeroDivisionError` and `TypeError`.
> 2.  Incorporate type hints for all parameters and the return value.
> 3.  Add a detailed Google-style docstring explaining the function, its arguments, and what it returns.
> 4.  Ensure the code adheres to PEP 8 standards.
>
> **Context:** Here is the function to refactor:
> ```python
> def calculate(a, b):
>   return a/b
> ```
>
> **Format:** Provide only the refactored Python code in a single code block.

This structured prompt will yield a far superior, production-ready result.

## 🤝 How to Contribute

Contributions are welcome and essential for making this project better! Please follow these steps:

1.  **Fork** the repository.
2.  Create a new branch: `git checkout -b feature/your-awesome-feature`
3.  Add your new prompts or improvements. Please try to follow the structured prompt format.
4.  Commit your changes: `git commit -m 'feat: Add new prompt for XYZ'`
5.  Push to the branch: `git push origin feature/your-awesome-feature`
6.  Submit a **Pull Request**.

Please read our [CONTRIBUTING.md](https://github.com/YOUR_USERNAME/Awesome-Developer-Prompts/blob/main/CONTRIBUTING.md) file for more detailed guidelines.

## ⚖️ License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/YOUR_USERNAME/Awesome-Developer-Prompts/blob/main/LICENSE) file for details.
