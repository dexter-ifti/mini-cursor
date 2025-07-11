# mini-cursor 🧠

**mini-cursor** is a terminal-based AI coding assistant designed to streamline full-stack project development. Leveraging AI capabilities, it assists developers in generating boilerplate code, managing project structures, and executing commands directly from the terminal.

## 🚀 Features

* **Terminal-Based Interface**: Interact with mini-cursor entirely through the terminal, eliminating the need for a graphical user interface.
* **Full-Stack Project Generation**: Automatically create project structures for both frontend and backend applications.
* **Code Generation**: Generate code snippets or entire files for various components, including React components, Express routes, and more.
* **Command Execution**: Run shell commands like `npm install`, `pip install`, and others directly through mini-cursor.
* **Contextual Understanding**: Analyze existing project files to provide context-aware suggestions and modifications.
* **File Operations**: Read, write, and modify files as needed to implement requested features or changes.

## 🛠️ Tools Utilized

* **command\_exec**: Executes terminal commands.
* **read\_file**: Reads and analyzes file contents.
* **write\_file**: Creates or updates files with specified content.
* **scan\_directory**: Lists files in a directory to understand project structure.
* **analyze\_code**: Analyzes existing code to make informed modifications.

## 📦 Requirements

* Python 3.6 or higher
* Gemini API key

## ⚙️ Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/dexter-ifti/mini-cursor.git
   cd mini-cursor
   ```



2. **Create a `.env` File**:

   ```bash
   echo "GOOGLE_API_KEY=your_api_key_here" > .env
   ```



3. **Install Required Packages**:

   ```bash
   pip install requirements.txt
   ```


## 🧪 Usage

Run the mini-cursor assistant using:

```bash
python cursor_agent.py
```




