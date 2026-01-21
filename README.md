# LangChain Practice

This repository contains Jupyter notebooks and Python scripts for practicing and understanding LangChain concepts, including prompt templates, chains, tools, memory, middleware, and structured outputs.

---

## Project Structure

```
.
├── langchain_Basics_1.ipynb
├── langchain_Basics_2.ipynb
├── messages.ipynb
├── middleware.ipynb
├── mode_integration.ipynb
├── structured_output.ipynb
├── tools.ipynb
│
├── main.py
├── updatedlangchain/
│
├── .env
├── .gitignore
├── .python-version
├── pyproject.toml
├── requirements.txt
├── uv.lock
└── README.md
```

---

## Requirements

- Python 3.10+
- uv Python package manager.
- Jupyter Notebook.
- OpenAI, Groq, GoogleAPI / compatible LLM API keys used.

---

## Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/langchain-practice.git
cd langchain-practice
```

### 2. Install dependencies using uv

```bash
uv sync
```

This will install all dependencies from `pyproject.toml` and `uv.lock`.

---

## Environment Variables

Create a `.env` file in the project root:

```
OPENAI_API_KEY=your_api_key_here
```

`.env` is ignored by git.

---

## Running Jupyter Notebooks

```bash
uv run jupyter notebook
```

Open any `.ipynb` file and execute cells.

---

## Running Python Script

```bash
uv run python main.py
```

---

## Notes

- Notebooks cover individual LangChain concepts.
- `updatedlangchain/` contains helper modules.
- `uv.lock` ensures reproducible environments.

---
