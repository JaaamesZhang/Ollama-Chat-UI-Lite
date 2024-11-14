# Ollama Chat UI Lite

Ollama Chat is a pure frontend UI application based on Ollama, designed to interact with the Ollama model through a simple interface.

## Features

- **Pure frontend application**, compatible with other languages.
- **Supports model switching**, automatically saves model settings.
- **Markdown rendering**, using [Marked.js](https://github.com/markedjs/marked) for rendering Markdown, and mathematical formulas processed by [MathJax](https://www.mathjax.org/).
- **Easy deployment**, all dependencies are small and fast to deploy.

## Instructions

### 1. Prerequisites

Ensure that you have installed [Ollama](https://ollama.com/) and downloaded the necessary model.

### 2. Install Ollama Chat UI Lite

Ensure that your local directory structure looks like this:

```plaintext
(any folder)
├── app.py                      # Flask server script
└── templates/                  # Folder must be named "templates"
    └── index.html              
```

Make sure you have Flask installed:

```bash
pip install flask
```

### 3. Run Ollama Chat UI Lite

Simply run `app.py`, and then open your browser and navigate to `http://127.0.0.1:5000/`. Enter the name of the downloaded model in the model input box to start using it.

## Feedback and Support
This is a high school student's first GitHub project. If you found this project useful or interesting, please consider giving it a star! If you encounter any issues, feel free to contact me. Thank you for your support 😄🎉
