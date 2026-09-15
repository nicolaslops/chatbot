# CHATBOT

## About the Project

This project consists of the development of an intelligent virtual assistant focused on technology education and developer support. Built in Python through the `dsa_assistente.py` script, the application creates an interactive chatbot that consumes a large language model (LLM) through a direct API integration.

The main feature of the assistant is its specialization and logical scope control. The project defines a strict system instruction (system prompt) before processing user requests. This instruction guides the AI to act exclusively as a Python specialist, refusing or redirecting questions outside the language's scope, creating a more focused technical support tool.

---

## Features

* Clean, user-friendly, and responsive web interface.
* Authentication and connection to the AI model through API key management.
* Prompt engineering (*system prompting*) applied in the application code to restrict the model's scope.
* Automated scope filtering that limits responses and technical support to topics related to the Python programming language.

---

## Technologies Used

* **Python 3**
* **Streamlit** (framework for building web applications and data dashboards)
* **LLM API** (integration with a large language model provider)

---

## Objective

The main objective of this project is to explore the development of Generative AI applications and prompt engineering techniques. The technical focus is on understanding how to build modern user interfaces with Python without relying on complex front-end frameworks by using Streamlit, managing local AI project dependencies through isolated virtual environments (`.venv`), and configuring the behavior and scope of an LLM.

---

## Learning Outcomes

During the development of this project, the following concepts were applied:

* Isolating and managing project dependencies using Python virtual environments (`.venv`).
* Creating package manifest files (`requirements.txt`) to list and install all required third-party libraries.
* Using the Streamlit ecosystem to dynamically render chat interfaces, conversation histories, and text inputs.
* Configuring and injecting system prompts to guide and constrain the behavior of an AI model.
* Managing credentials and API keys for third-party services securely.

---

## How to Run

1. Make sure Python is installed on your machine.
2. Navigate to the project folder through the terminal:

```bash
cd CHATBOT
```

3. Activate the virtual environment. Commands vary depending on the operating system:

**Windows:**

```bash
.venv\Scripts\activate
```

**Linux/macOS:**

```bash
source .venv/bin/activate
```

4. Install the dependencies listed in the project:

```bash
pip install -r requirements.txt
```

5. Make sure your API key is configured through the project's configuration or environment variables.

6. Run the application using Streamlit:

```bash
streamlit run dsa_assistente.py
```

---

## Project Structure

```text
CHATBOT/
│
├── .venv/               # Virtual environment with installed dependencies
├── .vscode/             # Editor workspace configuration
├── dsa_assistente.py    # Main chatbot and Streamlit interface
├── requirements.txt     # Project dependency list
└── README.md
```

---

## License

This project was developed exclusively for educational and learning purposes.

Developed as a hands-on exercise in building intelligent AI tools, prompt engineering, and rapid web application development using Streamlit and Python.
