<div align="center">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=FFC107" alt="Stars Badge"/>
  <img src="https://img.shields.io/github/forks/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=8BC34A" alt="Forks Badge"/>
  <img src="https://img.shields.io/github/contributors/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&logo=github&color=03A9F4" alt="Contributors Badge"/>
  <img src="https://img.shields.io/github/license/YOUR_USERNAME/Awesome-Developer-Prompts?style=for-the-badge&color=f44336" alt="License Badge"/>
</div>

<h1 align="center">
  Awesome Developer Prompts (开发者AI提示词大全)
</h1>

<p align="center">
  专为开发者打造的AI编程提示词工程指南。精选高质量Prompts，覆盖代码生成/重构/调试/测试/DevOps全流程。最佳实践适配GPT-4、Gemini、Copilot等模型，最大化提升编码效率。
</p>

<p align="center">
  <a href="./README.md"><strong>English</strong></a> | <a href="./README.zh-CN.md"><strong>中文</strong></a>
</p>

---

## 🚀 项目简介

在AI大模型时代，开发者拥有了一个前所未有的强大伙伴。然而，要从AI那里获得精确、健壮、可用于生产环境的响应，一个简单的问题是远远不够的。泛泛的提示词往往只能得到泛泛、不完整甚至不安全的代码。

本仓库是一个精心策划的、专为软件开发者设计的**提示词工程模式与最佳实践**合集。我们的目标是帮助你将AI助手从一个简单的代码补全工具，转变为一个资深的虚拟技术伙伴。

## ✨ 特点

本指南系统性地整理了覆盖软件开发全生命周期的提示词：

-   **💻 代码生成与重构:** 根据设计模式生成样板代码、实现复杂算法、以现代最佳实践重构老旧代码。
-   **🐞 调试与错误分析:** 精准定位Bug根源、解释复杂的堆栈跟踪、执行代码审查（Code Review）以发现潜在问题。
-   **✍️ API设计与文档:** 设计RESTful/GraphQL API结构、自动生成API文档、创建请求与响应示例。
-   **🗃️ 数据库与SQL:** 编写和优化复杂的SQL查询、设计数据库Schema、生成ORM模型代码。
-   **🧪 测试用例生成:** 创建单元测试、端到端（E2E）测试脚本、覆盖关键的边缘（Edge Cases）场景。
-   **⚙️ DevOps与自动化:** 编写CI/CD流水线配置、生成Dockerfile/K8s清单、编写自动化脚本。
-   **🏛️ 系统与架构设计:** 进行技术选型对比、撰写架构设计文档初稿。

## 🔧 如何使用

获得出色AI响应的关键在于提供出色的提示词。我们推荐使用结构化的方法以达到最佳效果。一个强大的提示词应包含以下要素：

1.  **角色 (Persona):** 为AI分配一个角色（例如：“你是一名资深的后端开发专家，精通Python和性能优化”）。
2.  **上下文 (Context):** 提供所有必要的背景信息，包括编程语言、框架、现有代码以及具体问题。
3.  **任务 (Task):** 清晰地定义你希望AI做什么。描述应尽量具体，并将复杂任务分解。
4.  **格式 (Format):** 指定你期望的输出格式（例如：“请将结果以单个JSON文件的形式提供”，“使用Markdown和Python代码块进行回复”）。

## 💡 示例：重构一个Python函数

让我们看看一个简单提示词和本指南中的结构化提示词之间的巨大差异。

#### ❌ 简单提示词

> “重构这个python函数”

AI或许会给你一个略好的版本，但很可能会缺少错误处理、文档等关键要素。

#### ✅ 结构化提示词 (源于本仓库)

> **角色:** 你是一名资深的Python开发工程师，擅长编写健壮、可维护且文档完善的代码。
>
> **任务:** 请重构下面的Python函数。你的重构必须达到以下目标：
> 1.  添加全面的错误处理，以应对潜在的 `ZeroDivisionError` 和 `TypeError`。
> 2.  为所有参数和返回值添加类型提示（Type Hints）。
> 3.  添加一个详细的Google风格文档字符串（Docstring），解释函数功能、参数和返回值。
> 4.  确保代码遵循PEP 8编码规范。
>
> **上下文:** 这是需要重构的函数：
> ```python
> def calculate(a, b):
>   return a/b
> ```
>
> **格式:** 请仅在单个代码块中提供重构后的Python代码。

这个结构化的提示词将会产出一个质量远超前者、可直接用于生产环境的结果。

## 🤝 如何贡献

我们非常欢迎并感谢所有的贡献！请遵循以下步骤：

1.  **Fork** 本仓库。
2.  创建一个新的功能分支: `git checkout -b feature/your-awesome-feature`
3.  添加你的新提示词或改进。请尽量遵循我们推荐的结构化提示词格式。
4.  提交你的更改: `git commit -m 'feat: 为XYZ添加新提示词'`
5.  将分支推送到你的Fork仓库: `git push origin feature/your-awesome-feature`
6.  提交一个 **Pull Request**。

请阅读我们的 [CONTRIBUTING.md](https://github.com/YOUR_USERNAME/Awesome-Developer-Prompts/blob/main/CONTRIBUTING.md) 文件以了解更详细的指南。

## ⚖️ 许可证

本项目采用 **MIT许可证**。详情请见 [LICENSE](https://github.com/YOUR_USERNAME/Awesome-Developer-Prompts/blob/main/LICENSE) 文件。
