Working through the [realpython.com Build and LLM RAG chatbot with langchain tutorial](https://realpython.com/build-llm-rag-chatbot-with-langchain/) as part of my project to learn Python.

I'm using venv to manage the virtual environment, and coding in Windows. The following notes to self would probably be obvious to any experienced Python developer.

### To create a virtual environment ```venv```, as a one-off step
```python -m venv venv```

### To activate the virtual environment ```venv``` (Windows command prompt or PowerShell)
```
PS> venv\Scripts\activate
(venv) PS>
```

### To install dependencies, in Windows (one-off, or any time you merge an updated requirements.txt)
```pip install -r requirements.txt```

### To update requirements.txt (any time you've added or updated a dependency)
```pip freeze > requirements.txt```
