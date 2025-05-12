
# 🐳 Dockerfile Generator

A GenAI-powered tool that generates optimized Dockerfiles based on programming language input. This project uses Ollama with the Llama3 model to create Dockerfiles following best practices.

---

## 📋 Prerequisites

### Installing Ollama

#### For Linux:
```bash
curl -fsSL https://ollama.com/install.sh | sh
````

#### For MacOS:

```bash
brew install ollama
```

### Start Ollama Service

```bash
ollama serve
```

### Pull Llama3 Model

```bash
ollama pull llama3.2:1b
```

---

## 🚀 Project Setup

### Create Virtual Environment

```bash
python3 -m venv venv
```

For Linux/MacOS:

```bash
source venv/bin/activate
```

For Windows:

```bash
.\venv\Scripts\activate
```

### Install Dependencies

```bash
pip3 install -r requirements.txt
```

### Run the Application

```bash
python3 generate_dockerfile.py
```

---

## 💡 How It Works

1. The script takes a programming language as input (e.g., Python, Node.js, Java).
2. It connects to the **Ollama API** running locally.
3. It generates an optimized Dockerfile with best practices for the specified language.
4. It returns the Dockerfile content with explanatory comments.

---

## 📝 Example Usage

```bash
python3 generate_dockerfile.py
Enter programming language: python
```

The generated Dockerfile will be displayed...

---

## 🏆 Troubleshooting

* **Ensure the Ollama service is running** before executing the script.
* **Make sure the correct model is downloaded** (`llama3.2:1b`).
* **Adapt best practices for other programming languages** as needed.

---

## 📢 License

This project is licensed under the MIT License - see the LICENSE file for details.

```

This layout separates the sections clearly and follows the GitHub markdown conventions, making it easy to navigate. You can further customize it as necessary!
```
