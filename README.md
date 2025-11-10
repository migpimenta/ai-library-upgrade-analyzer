# Python Notebook Project

This repository contains a Jupyter notebook for data analysis and experimentation.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- [uv](https://github.com/astral-sh/uv) package manager

### Installation

1. Install `uv` if you haven't already:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Create a virtual environment and install dependencies:
```bash
uv venv
source .venv/bin/activate  # On macOS/Linux
uv pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

   **Option A: Using Jupyter in the browser**
   ```bash
   jupyter notebook
   ```
   Then open `notebook.ipynb` in the Jupyter interface.

   **Option B: Using VS Code**
   - Open the workspace in VS Code
   - Install the Jupyter extension if not already installed
   - Open `notebook.ipynb` - it will open in VS Code's notebook editor
   - Select the Python interpreter from your virtual environment (`.venv`) when prompted

## Usage

The notebook is now ready to use. You can run cells sequentially or modify them as needed.
