# langchain-rag-assignment
Generative AI Assignment – LangChain RAG Pipeline 
 -Tech Stack Used
LangChain
Vector Store: FAISS
Embeddings: Sentence Transformers (MiniLM)
LLM: Mistral via Ollama

Document: attention_is_all_you_need.pdf

 Task 1 – Theoretical Questions
Included in Task1_Task2_Document.docx (submitted as Word file)

Task 2 – Sequence-to-Sequence Model using LSTM
Implementation and explanation included in the same DOC file above

 Task 3 – Setup LangChain RAG Pipeline
Loaded attention_is_all_you_need.pdf
Chunked the document
Converted chunks into embeddings
Stored embeddings in FAISS
Built RetrievalQA pipeline with LangChain

 Task 4 – Test with Queries
Asked 5 meaningful questions from the PDF
Logged the answers and the retrieved document chunks
Compared results with and without the retriever

 Task 5 – Customized Prompt Template
Citations
Disclaimers
Structured bullet-point formatting

- Installation & Run Instructions
 Install Requirements
bash
Copy
Edit
pip install langchain chromadb faiss-cpu sentence-transformers
Run Notebook (Option 1 – Colab)
Open LangChain_RAG_Assignment.ipynb in Google Colab

Upload the PDF when prompted
Run cells step-by-step


# Create virtual environment (optional but recommended)
python -m venv rag_env
source rag_env/bin/activate  # or rag_env\Scripts\activate on Windows

# Install required packages
pip install -r requirements.txt

# Launch notebook
jupyter notebook LangChain_RAG_Assignment.ipynb
