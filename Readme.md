# Offline FAQ/Reasoning Chatbot with RAG

Create a RAG from any data source (docx, txt, etc) and use it as a FAQ chatbot without answering out of context answer and streaming. 
Please keep in mind that the default data source is docx, in order to ingest from a different source please look into create_data.py.

## Description

Provide documents, get answers. The prompt has been formatted to answer like a chatbot on a company website specifically.

## Getting Started

### Dependencies

* Use Python 3.9
* Setup [Ollama](https://github.com/ollama/ollama/tree/main) with llama 2 7b-chat or any other model from Ollama (You will have to make changes in query.py)
* pip install -r requirements.txt
* Keep files in data/Docx or change the path in create_data.py


### Executing program

* First run create_data.py 
```
python create_data.py
```

* Second run query.py (It takes string in command line argument as input)
```
python query.py "What is your product"
```
