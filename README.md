# Getting Started with ollama-chatbot
This is a chatbot application built using Ollama and Streamlit. In this guide, we will walk you through the process of setting up and running the project on your local machine.

## Before You Begin 
To get started with this project, you will need to have the following tools installed on your machine:
- Python 3.11 [https://www.python.org/downloads/release/python-3110/](https://www.python.org/downloads/release/python-3110/)
- pip [https://pip.pypa.io/en/stable/installation/](https://pip.pypa.io/en/stable/installation/)
- Ollama [https://ollama.com/](https://ollama.com/)
- Docker (for DevContainer support)
- Visual Studio Code with Remote - Containers extension

## Development with DevContainer

This project includes a DevContainer configuration for a consistent development environment:

### Features
- Python 3.11 base image
- Pre-installed development tools:
  - Black (code formatter)
  - Pylint (linter)
  - VSCode Python extensions
- Automatic dependency installation
- Streamlit port (8501) pre-configured for forwarding

### Getting Started with DevContainer

1. Install Prerequisites:
   - Docker
   - Visual Studio Code
   - Remote - Containers extension

2. Clone the repository:
   ```bash
   git clone https://github.com/adhika16/ollama-chatbot.git
   ```

3. Open the project in VSCode:
   ```bash
   code ollama-chatbot
   ```

4. When prompted, click "Reopen in Container" or:
   - Open Command Palette (Ctrl+Shift+P)
   - Select "Remote-Containers: Reopen in Container"

### Alternative Setup Methods

#### Local Virtual Environment Setup
1. Create a virtual environment:
   ```bash
   python -m venv <venv_name>
   ```

2. Activate the virtual environment:
   - On Windows:
     ```shell
     <venv_name>\Scripts\activate
     ```
   - On Unix or MacOS:
     ```bash
     source <venv_name>/bin/activate
     ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

5. Open a web browser and navigate to `http://localhost:8501` to see the chatbot in action!

## License

This project is licensed under the MIT License - see the LICENSE file for details.