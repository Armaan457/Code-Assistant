# Code Assistant
A simple QnA chatbot using **Meta's Codellama** designed specifically for coding tasks integrated with message history for easier reference during chat.

# Technologies used
**Web Interface**: Gradio <br>
**LLM**: Codellama (via Ollama) <br>

# Setup

Clone the repository:

```sh
> git clone https://github.com/Armaan457/Code-Assistant.git
```

Setup LLM locally using Ollama:

```sh
> ollama create CodeChamp -f modelfile 
```

Create and activate a virtual environment:

```sh
> python -m venv venv
> venv\Scripts\activate
```

Install dependencies:

```sh
> pip install -r requirements.txt
```

Run the development server:

```sh
> python app.py
```
