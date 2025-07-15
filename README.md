# RAG-QuestionAnswering-System

A Google Colab project that implements **Retrieval-Augmented Generation (RAG)** — combining a retriever (e.g., ChromaDB) with a generator (e.g., OpenAI GPT) to build a context-aware question-answering system using custom documents.

---

## 🔍 What is RAG?

**RAG** enhances LLMs by retrieving relevant information from external sources and passing it to the model to generate accurate, grounded responses — reducing hallucination and improving domain relevance.

---

## 🧠 Architecture


---

## ⚙️ Tools Used

- `Google Generative AI API` (Gemini 1.5 Flash model)
- `LangChain` (for chaining and orchestration)
- `ChromaDB` (vector store)
- `SentenceTransformers` / `OpenAI Embeddings`
- `Google Colab` (notebook interface)

---

## 🚀 How to Run

1. Open the notebook in Colab.
2. Install dependencies.
3. Upload a document.
4. Run the cells to:
   - Chunk and embed text
   - Store in ChromaDB/FAISS
   - Ask questions and receive answers

---

## ✅ Use Cases

- Legal/Medical/Technical document Q&A  
- Custom document-based assistants  
- Educational bots with document support

---

## 📚 References

- [RAG Paper](https://arxiv.org/abs/2005.11401)  
- [LangChain Docs](https://docs.langchain.com/)  
- [ChromaDB](https://www.trychroma.com/)  
- [OpenAI API](https://platform.openai.com/)

---

## 📬 Contact

Questions? Feedback? Feel free to reach out or open an issue.
