# 🐍 AcadHack CLI (Command Line Interface) [WIP]

This repository contains the original, architecture-agnostic core logic for AcadHack. It is designed for developers, advanced users, and those running cross-platform (Linux, macOS, Windows CLI) who prefer manual configuration.

## ⚙️ Core Architecture

This CLI is the engine that powers the entire AcadHack project:

*   **Technology:** Python, Selenium, Google Gemini API.
*   **Design:** Modular script structure (config, scraper, solver, main).
*   **Portability:** The Python scripts are highly portable and run on any OS with Python and Chrome installed.

## ⚠️ Important Note on Usage (Manual Setup Required)

The CLI version requires **manual setup** of the Chrome browser before execution:

1.  Chrome must be launched manually with the remote debugging flag enabled (e.g., `chrome --remote-debugging-port=9222`).
2.  The script then **attaches** to this running instance.

For a simpler, one-click experience on Windows, please refer to the `acadhack-gui` repository.

## Installation & Setup

1.  Clone this repository.
2.  Install dependencies: `pip install -r requirements.txt` (or list key dependencies).
3.  Launch Chrome manually as described above.
4.  Run the script: `python main.py`

## 📚 Related Project

*   **User-Friendly GUI:** The full-featured desktop application can be found in the [`acadhack-gui`](https://github.com/acadhack/acadhack-gui) repository.

## Contributing

We welcome contributions to improve the efficiency and modularity of the core automation logic.
