# AI-Chatbot-RAG

A Retrieval-Augmented Generation (RAG)-based AI chatbot that answers queries based on uploaded documents. The chatbot utilizes **LangChain**, **FAISS**, and **Ollama** to efficiently retrieve relevant document chunks and generate responses using a locally hosted LLM.

## Features
- **Document-Based Question Answering**: Upload PDFs, extract text, and query relevant information.
- **RAG (Retrieval-Augmented Generation)**: Combines document retrieval with LLM-based response generation.
- **FAISS for Efficient Vector Search**: Stores and retrieves document embeddings for fast and accurate responses.
- **Locally Hosted LLMs with Ollama**: Ensures fast and private inference.

## Installation
### Prerequisites
- Python 3.9+
- [Ollama](https://ollama.ai/) installed on your machine

### Clone the Repository
```bash
git clone https://github.com/TarunKumarRevelli/AI-Chatbot-RAG.git
cd AI-Chatbot-RAG
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
Run the chatbot notebook:
```bash
jupyter notebook
```
Open the `.ipynb` file and execute the cells to load the model, process documents, and run queries.

## Dependencies
The project requires the following dependencies:
```txt
ollama==0.4.4
streamlit==1.40.0
pdfplumber==0.11.4
langchain==0.3.14
langchain-core==0.3.29
langchain-ollama==0.2.2
langchain_community==0.3.14
langchain_text_splitters==0.3.5
unstructured>=0.16.12
unstructured[all-docs]>=0.16.12
onnx>=1.17.0
protobuf==5.29.2
chromadb>=0.4.22
Pillow==10.4.0
numpy==1.26.4
pytest==7.4.4
pytest-cov==4.1.0
coverage==7.4.0
pydantic==2.10.4
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Tarun Kumar Revelli](https://github.com/TarunKumarRevelli)
