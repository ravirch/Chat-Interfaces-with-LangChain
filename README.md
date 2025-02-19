# **Chat Interfaces with LangChain**  

This section covers multiple chat-based projects using **LangChain**, demonstrating different techniques for building interactive AI-powered chat applications.

---

## **📌 Features**  
✅ **Conversational AI with OpenAI & Ollama**  
✅ **RAG-based chatbots for document interaction**  
✅ **Conversational memory for contextual responses**  
✅ **SQL-integrated chatbot for structured queries**  
✅ **Search engine chatbot using LangChain agents**  

---

## **📂 Folder Structure**  

```
│── 1-Q&A Chatbot Using OpenAI/
│   ├── app.py                  # Chatbot powered by OpenAI LLM  
│── 2-Q&A Chatbot Using Ollama/
│   ├── app.py                  # Chatbot using Ollama models  
│── 3-RAG Document Q&A/
│   ├── research_papers/        # Sample documents for testing  
│   ├── app_huggingfaceembedding.py # Chatbot using Hugging Face embeddings  
│   ├── main.py                 # Main script for RAG-based interaction  
│── 4-RAG Q&A Conversation/
│   ├── app.py                  # Chatbot with memory-enhanced Q&A  
│   ├── temp.pdf                # Example document for testing  
│── 5-Search Engine/
│   ├── app.py                  # Chatbot acting as a search engine  
│   ├── tools_agents.ipynb       # LangChain tools & agents integration  
│── 6-Chat SQL/
│   ├── app.py                  # SQL chatbot for structured queries  
│   ├── sqlite.py               # SQLite database management  
│   ├── student.db              # Sample database  
```

---

## **🚀 Project Descriptions & Usage**  

### **1️⃣ Q&A Chatbot Using OpenAI**
- Uses **OpenAI LLMs** to answer queries.  
- Run the chatbot:  
  ```bash
  streamlit run 1-Q&A Chatbot Using OpenAI/app.py
  ```

### **2️⃣ Q&A Chatbot Using Ollama**
- Uses **Ollama models** for answering queries.  
- Run the chatbot:  
  ```bash
  streamlit run 2-Q&A Chatbot Using Ollama/app.py
  ```

### **3️⃣ RAG Document Q&A**
- Implements **Retrieval-Augmented Generation (RAG)** with **Hugging Face embeddings**.  
- Run the chatbot:  
  ```bash
  streamlit run 3-RAG Document Q&A/main.py
  ```

### **4️⃣ RAG Q&A Conversation**
- Chatbot with **memory-enabled document interaction**.  
- Run the chatbot:  
  ```bash
  streamlit run 4-RAG Q&A Conversation/app.py
  ```

### **5️⃣ Search Engine with LangChain Agents**
- Uses **LangChain tools & agents** to perform intelligent search.  
- Run the chatbot:  
  ```bash
  streamlit run 5-Search Engine/app.py
  ```

### **6️⃣ Chat SQL – SQL-Based Chatbot**
- Chatbot capable of querying an **SQLite database**.  
- Run the chatbot:  
  ```bash
  streamlit run 6-Chat SQL/app.py
  ```

---

This **Chat Interfaces** section is part of the **[Generative AI with LangChain Python](https://github.com/ravirch/Generative-AI-with-LangChain-Python)** repository. 🚀  
