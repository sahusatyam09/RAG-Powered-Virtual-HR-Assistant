# RAG-Powered-Virtual-HR-Assistant
An intelligent, document-aware HR assistant that extracts and explains HR policies from internal PDFs like Employee Handbooks.

# RAG-Powered Virtual HR Assistant

This project is an intelligent, document-aware assistant that answers HR policy questions using Retrieval-Augmented Generation (RAG).

## Features
- Retrieves answers directly from the Employee Handbook PDF.
- Uses LangChain, Falcon-7B-Instruct, and ChromaDB.
- Works offline for better security.
- Minimizes hallucination using retrieval and strict prompt templates.

## How to Run

1. Clone this repository:
git clone https://github.com/yourusername/rag-hr-assistant.git
cd rag-hr-assistant

2. Install dependencies:
pip install -r requirements.txt

3. Run in Google Colab:
- Open the notebook `rag_hr_assistant.ipynb`
- Run all cells
- Upload your Employee Handbook PDF

4. Ask Questions:
Example:
Q: How many sick leaves are allowed per year?
A: Full-time employees are entitled to 12 sick leaves annually.

## Tech Stack
- LangChain → Orchestrates the RAG pipeline
- ChromaDB → Vector database for HR documents
- Falcon-7B-Instruct → LLM for generating answers
- all-MiniLM-L6-v2 → Embedding model
- Google Colab → Cloud GPU for running models

## Next Steps
- Add a Gradio web interface for easier usage.
- Expand to multiple HR policy documents.

---

### Open in Google Colab
[Open In Colab](https://colab.research.google.com/github/yourusername/rag-hr-assistant/blob/main/rag_hr_assistant.ipynb)

---

This project helps employees quickly find HR policy answers without manually searching PDFs.
