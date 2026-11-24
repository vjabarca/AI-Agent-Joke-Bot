# AI Agent Joke Bot

An AI-powered joke bot built in a Jupyter Notebook. This repository contains the notebook implementation and a visual asset for the project.

> **Note:** The repository currently exposes the notebook (`AI_Joke_Bot.ipynb`) and an image (`joke bot.png`). The implementation details, model/provider, API requirements, and exact dependencies should be confirmed from the notebook before running the project. The setup below provides a standard Jupyter workflow.

## Repository Contents

```text
AI-Agent-Joke-Bot/
├── AI_Joke_Bot.ipynb   # Main notebook
└── joke bot.png        # Project image
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vjabarca/AI-Agent-Joke-Bot.git
cd AI-Agent-Joke-Bot
```

### 2. Set up Python

Python 3.9 or newer is a reasonable starting point for a modern notebook environment. If the notebook specifies a different version, follow that requirement.

Create and activate a virtual environment:

```bash
python -m venv .venv

# macOS / Linux
source .venv/bin/activate

# Windows PowerShell
.venv\Scripts\Activate.ps1
```

### 3. Install Jupyter

```bash
python -m pip install --upgrade pip
python -m pip install jupyter
```

Install any additional packages imported by `AI_Joke_Bot.ipynb`:

```bash
python -m pip install <package-name>
```

### 4. Launch the notebook

```bash
jupyter notebook
```

In the browser window, open **`AI_Joke_Bot.ipynb`** and run the cells from top to bottom.

## Configuration

If the notebook uses an external AI service, you may need an API key or other credentials.

- Check the notebook for the provider and required environment-variable names.
- Keep credentials private. Do not commit API keys, passwords, or `.env` files.
- If credentials are required, store them in environment variables or a local `.env` file and load them from the notebook.
- Never paste a real API key into a notebook cell that will be committed to GitHub.

## Usage

1. Start Jupyter using the command above.
2. Open `AI_Joke_Bot.ipynb`.
3. Run the notebook cells in order.
4. Follow any prompts or configuration instructions displayed by the notebook.

## Troubleshooting

- **Module not found:** Install the missing package in the same Python environment used by Jupyter, then restart the notebook kernel.
- **Authentication or API errors:** Verify that the required credentials are configured and that the account has access to the selected service.
- **Changes are not taking effect:** Restart the notebook kernel and run the cells again from the beginning.

## Contributing

Contributions, suggestions, and bug reports are welcome. For substantial changes, consider opening an issue first to discuss the proposed update.

## License

No license file is currently visible in the repository. Unless a license is added, the project should be treated as having no explicit open-source reuse license. Add a `LICENSE` file if you want to grant others specific permissions to use, modify, or distribute the project.
