# AI Agent Velora ✨

**Your intelligent partner for refactoring and documenting unstructured codebases, powered by IBM Watsonx.ai.**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://marketplace.visualstudio.com/items?itemName=cryptarchs.velora)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by: IBM Watsonx.ai](https://img.shields.io/badge/Powered%20by-IBM%20Watsonx.ai-blue)](https://www.ibm.com/watsonx)

AI Agent Velora is a VS Code extension designed to bring order to chaos. It analyzes your messy Python projects, understands your goals, and uses the power of IBM's foundation models to intelligently restructure your files, fix broken imports, and generate professional-grade documentation.

---

### Demo

![AI Agent Velora in Action](https://raw.githubusercontent.com/Ajayace03/velora-agent-vscode/main/images/demo.gif) 
*A sample of Velora restructuring a project and generating its documentation.*

---

## Core Features

* **🤖 Persona-Driven Refactoring:** Velora tailors its approach based on your role. Whether you're a Developer, Data Scientist, Researcher, or Student, you'll get a project structure that fits your workflow.
* **🧠 Intelligent Code Restructuring:** Moves files into a clean, standard project layout (e.g., `src/`, `tests/`, `docs/`) based on AI analysis.
* **🔧 Automated Import Fixing:** Uses Abstract Syntax Trees to automatically rewrite relative imports in your Python files, ensuring your code still works perfectly after being moved.
* **📝 AI-Generated Documentation:** Generates a comprehensive `README.md` and a detailed `PROJECT_WORKFLOW.md` for your newly structured project, explaining the architecture and data flow.
* **⚙️ Boilerplate Generation:** Automatically creates essential files like `.gitignore`, `requirements.txt`, and `setup.py` to professionalize your project.
* **📊 Real-time Logging:** Provides a detailed log of every action in the VS Code "Output" channel, so you're always in control.

## Requirements

* **VS Code** (version 1.85 or newer)
* **Python** (version 3.8 or newer)
* **An IBM Cloud Account** to access Watsonx.ai services.

## Setup & Configuration

Before you can use the agent, you need to provide it with your IBM Watsonx.ai credentials.

**1. Get Your IBM Credentials:**
   * Log in to your [IBM Cloud](https://cloud.ibm.com/) account.
   * Navigate to your **Watsonx.ai** project.
   * You will need to find three pieces of information:
     * **API Key:** This is your IBM Cloud API key. You can find or create this under `Manage > Access (IAM) > API keys`.
     * **Endpoint URL:** The URL for your Watsonx.ai instance region (e.g., `https://us-south.ml.cloud.ibm.com`).
     * **Project ID:** This is the unique GUID for your project, found in the "Manage" tab of your Watsonx.ai project settings.

**2. Configure the Extension in VS Code:**
   * Open VS Code Settings (`Ctrl + ,`).
   * Search for **"AI Agent Velora"** or **"AI Project Refactorer"**.
   * Fill in the three required fields with the credentials you obtained in the previous step.

   ![Configuration Screenshot](https://raw.githubusercontent.com/Ajayace03/velora-agent-vscode/main/images/settings.png) 
   ## How to Use

1.  Open an unstructured Python project folder in VS Code.
2.  Open the Command Palette (`Ctrl + Shift + P`).
3.  Run the command: **`AI Agent: Start New Project Refactoring`**.
4.  A new tab will open with a form. Fill in your persona and project goals.
5.  Click the **"Start Refactoring"** button.
6.  Watch the progress in the notification pop-ups and see the detailed logs in the **"AI Agent"** tab of the VS Code Output panel.

## Extension Settings

This extension contributes the following settings:

| Setting                                | Description                                               |
| -------------------------------------- | --------------------------------------------------------- |
| `ai-project-refactorer.ibmApiKey`      | **Required.** Your IBM Watsonx.ai API Key.                |
| `ai-project-refactorer.ibmUrl`         | **Required.** The endpoint URL for your Watsonx.ai instance. |
| `ai-project-refactorer.ibmProjectId`   | **Required.** The Project ID for your project in Watsonx.ai. |
| `ai-project-refactorer.pythonPath`     | (Optional) The absolute path to your Python executable.     |

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. Please feel free to fork the repo and create a pull request, or open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

*This extension was proudly built on August 17, 2025.*