# AI Engineering Playground 

This repository contains my personal Python development environment setup for AI engineering tasks. Please refer to it as a starting point for your own projects, when you need a consistent and reproducible development environment across different machines.

## 🌟 Key Features

- 🐳 Containerized development environment for consistency across machines
- 🐍 Latest Python with essential AI/ML libraries pre-installed
- ⚙️ Customizable VS Code settings optimized for AI development
- 🔧 Easy to extend and personalize for your specific needs

## 🛠️ Setup

### Prerequisites

- [VS Code](https://code.visualstudio.com/) (or [Cursor](https://cursor.com/))
- [Docker](https://www.docker.com/)
- [VS Code Remote](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

### Quick Start

1. Clone this repository:

    ```bash
    git clone https://github.com/alexnodeland/ai-engineering-workspace.git
    cd ai-engineering-workspace
    ```

2. Open the folder in VS Code (or [Cursor](https://cursor.com/)):

    ```bash
    code .
    ```

3. When prompted, click "Reopen in Container" or run the "Remote-Containers: Reopen in Container" command from the Command Palette (F1).

4. VS Code will build the devcontainer and install the Python packages specified in `requirements.txt`.

## 🎨 Customization

Tailor the environment to your needs:

- `.devcontainer/devcontainer.json`: Adjust container settings
- `.vscode/settings.json`: Modify VS Code configurations
- `requirements.txt`: Add or remove Python packages

## 💡 Why Use This Playground?

- **Consistency**: Ensure your AI projects work the same way across different machines
- **Efficiency**: Get started quickly with a pre-configured environment
- **Flexibility**: Easily modify the setup to match your project requirements
- **Collaboration**: Share your exact development environment with team members

## 🤝 Contributing

Found a way to improve this playground? Contributions are welcome! Feel free to fork, modify, and submit pull requests.

## 📝 License

This project is open-source and available under the MIT License.
