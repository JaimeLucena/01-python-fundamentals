# Python Fundamentals for LangChain
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Latest-orange)](https://jupyter.org/)
[![UV](https://img.shields.io/badge/UV-Package%20Manager-green)](https://github.com/astral-sh/uv)

Welcome! This repository contains Jupyter notebooks covering the essential Python fundamentals you need to start working with LangChain.

## 🎯 Purpose

Before diving into LangChain, you need to understand the Python basics that will actually be used in AI development. **You don't need to master everything in Python** - just the concepts and tools you'll encounter when building LangChain applications.

This course is designed to be:
- **Focused**: Only what you need for LangChain
- **Practical**: Real concepts you'll use daily
- **Quick**: Won't take much of your time
- **Foundation**: A solid base for AI development with LangChain

### Why This Matters

LangChain is a powerful Python framework for building AI applications. To use it effectively, you need to understand:
- Basic Python syntax
- Data structures (lists, dictionaries, sets)
- Control flow (loops, conditionals)
- Functions and decorators
- Object-oriented programming basics
- Modules and imports
- Context managers
- Environment variables
- Type hints

**💡 Pro Tip**: Use ChatGPT, Claude, or your favorite AI model to expand on any topic covered in the notebooks. These assistants are excellent for clarifying concepts and providing additional examples!

## 📚 Course Content

The notebooks are structured progressively to build your knowledge step by step:

1. **01_syntax_basics.ipynb** - Python syntax fundamentals
2. **02_data_structures_core.ipynb** - Lists, dictionaries, tuples, and sets
3. **03_control_flow.ipynb** - Conditionals, loops, and flow control
4. **04_functions_and_decorators.ipynb** - Function definitions and decorators
5. **05_classes_objects_oop_light.ipynb** - Object-oriented programming essentials
6. **06_modules_imports_debugging.ipynb** - Working with modules and debugging
7. **07_context_managers.ipynb** - Understanding context managers (`with` statements)
8. **08_env_and_secrets.ipynb** - Environment variables and secrets management
9. **09_typing_pydantic_vs_typedict.ipynb** - Type hints and validation

## 🚀 Setup

### Prerequisites

You'll need two tools to work with these notebooks:

### 1. UV - Modern Python Package Manager

**What is UV?**
UV is a fast, modern package and project manager for Python. It's significantly faster than pip and handles virtual environments seamlessly.

**Installation:**

```bash
# On macOS and Linux:
curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows:
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### 2. JupyterLab - Interactive Development Environment

**What is JupyterLab?**
JupyterLab is a web-based interactive development environment for notebooks, code, and data. It allows you to write and execute code in an interactive way, perfect for learning and experimentation.

## 📖 How to Use This Repository

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd 01-python-fundamentals
   ```

2. **Install dependencies:**
   ```bash
   uv sync
   ```

3. **Launch JupyterLab:**
   ```bash
   uv run jupyter
   ```

4. **Work through the notebooks in order** (01 through 09)

5. **Experiment!** Modify the code, try new examples, and use AI assistants to deepen your understanding

## 🎓 Learning Tips

- **Don't rush**: Take your time with each concept
- **Practice**: Modify the examples and create your own
- **Ask questions**: Use ChatGPT/Claude to clarify any doubts
- **Focus on understanding**: You don't need to memorize everything
- **Keep it practical**: Think about how each concept applies to LangChain

## 🔗 What's Next?

After completing these fundamentals, you'll be ready to dive into LangChain development! You'll have the Python knowledge needed to:
- Build AI-powered applications
- Understand LangChain's architecture
- Work with language models
- Create custom chains and agents
- Manage prompts and memory

## 🔗 Next Repository → LangChain Beginners

Once you finish these fundamentals, continue with the next step in your learning path:

👉 [02-langchain-beginners](https://github.com/jaimelucena/02-langchain-beginners)

That repository will guide you through:
	•	LangChain Expression Language (LCEL)
	•	Prompt templates and chain composition
	•	RAG (Retrieval-Augmented Generation) fundamentals
	•	Vector stores (Chroma / FAISS)
	•	LangGraph memory and modern AI app structure

🧠 You’ll move from learning Python for AI to building actual LLM applications.

## 📝 License

See the [LICENSE](LICENSE) file for details.

---

**Ready to start your LangChain journey? Begin with notebook 01! 🐍✨**