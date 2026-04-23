# langchain-new

## Setup

### Prerequisites

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) if you haven't already:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Initialize the project

If starting from scratch, scaffold the project with:

```bash
uv init
```

This creates `pyproject.toml`, `main.py`, `README.md`, and `.python-version`.

If cloning an existing project, install dependencies instead:

```bash
uv sync
```

### Activate the virtual environment

**macOS / Linux / Git Bash:**
```bash
source .venv/Scripts/activate
```

**PowerShell:**
```powershell
.venv\Scripts\Activate.ps1
```

**Command Prompt:**
```cmd
.venv\Scripts\activate.bat
```

### Run the project

```bash
uv run main.py
```
