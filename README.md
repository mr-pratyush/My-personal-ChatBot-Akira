# 🚀 Akira – Personal Generative AI Chatbot  

**Akira** is a personal Generative AI chatbot that I (Pratyush Gautam) designed and developed **end-to-end** to showcase how Large Language Models (LLMs) can be integrated with **retrieval-augmented pipelines**, embeddings, and custom frontends.  

Unlike pre-built solutions, Akira was crafted from scratch — covering **data ingestion, embedding generation, vector search, LLM orchestration, API integration, and frontend design**. The chatbot is capable of answering context-driven questions from a knowledge base in a reliable and interactive way.  

---

## 🌐 Live Preview & How to Access  

You can try **Akira Chatbot** directly from my portfolio website:  

👉 [Visit My Portfolio Website](https://mr-pratyush.netlify.app/)  

### Steps to Access:  
1. Open the website link above.  
2. Look for the **🤖 Bot Logo** on the homepage.  
3. Click the logo to launch **Akira Chatbot**.  
4. Type your query and start chatting with Akira.  
5. Choose the **intent** from the dropdown menu:  
   - **Personal** → Answers related to me (Pratyush’s profile & details).  
   - **Web** → Answers fetched from the web.  
   - **All (default)** → LLM decides dynamically from where to fetch the answer.  
6. Use the **three-dot menu** to start a fresh chat window or close the current one.  
7. Provide feedback by liking 👍 or disliking 👎 any response.  

---

## 🖼️ Screenshots  

### 🔹 Step 1 – Homepage with Bot Icon  
![Homepage Preview](./docs/homepage.png)  

### 🔹 Step 2 – Chatbot Window  
![Chatbot Preview](./docs/chatbot.png)  

### 🔹 Step 3 – Start Chatting  
![Conversation Preview](./docs/conversation.png)  

---

## 🛠️ Tech Stack  

- **Backend Frameworks**: Python, FastAPI  
- **LLM Orchestration**: LangChain, LangGraph  
- **Embeddings & Vector Store**: Cohere / Pinecone  
- **Frontend**: Custom-designed React interface (UI/UX designed by me)  
- **Data Pipeline**: Document ingestion, chunking, embedding, retrieval, indexing  
- **Web Search**: Tavily Search  
- **Deployment Ready**: Works with Docker & API-first architecture  

---

## ✨ Features  

- **End-to-End RAG Workflow**: Query → Embeddings → Vector Search → Context Retrieval → LLM Response  
- **Custom Frontend**: Clean, user-friendly UI designed by me  
- **Confidence Scoring**: Helps users evaluate reliability of answers  
- **Context Awareness**: Fetches relevant chunks for precise responses  
- **Semantic Search Optimization**: Uses vector similarity for accuracy  
- **Scalable Backend**: Easily extensible for enterprise use cases  
- **Best View on Desktop** (mobile support still in progress)  

---

## ⚡ Current Limitations  

- Limited to the scope of the ingested knowledge base (not a general-purpose AI like ChatGPT).  
- Requires fine-tuning for handling very large document collections.  
- The **first response currently takes 50–60 seconds**, as I’m using a **free-tier cloud service** to host the backend.  
- Although I am not a professional frontend developer, the **entire UI was designed and built by me**. It is fully functional but can be further enhanced with animations and advanced styling.  
- The project is still in an **experimental phase**, so no public deployment has been made yet.  
- Mobile view has **limited features and optimizations**; I’m actively working to improve the mobile experience.  

---

## 📌 Future Improvements  

- Integration with advanced **LangGraph agent workflows**  
- Support for **streaming responses**  
- Addition of **chat history**  
- Enhanced **confidence scoring & response quality**  
- Reducing latency (removing initial delay, once better hosting resources are available)  
- **User authentication & role-based access** for enterprise use cases  
- Richer **frontend interactivity** with improved UI/UX and animations  

---

## 🏗️ System Architecture  

```text
User Query
    │
    ▼
Frontend (React UI)
    │
    ▼
FastAPI Backend
    │
    ▼
LangChain / LangGraph Pipeline
    │
 ┌───────────────┐
 │ Embeddings    │
 │ (Cohere, etc) │
 └───────────────┘
    │
    ▼
Vector Database (Pinecone)
    │
    ▼
Context Retrieval
    │
    ▼
LLM Response Generation
    │
    ▼
Final Answer → Displayed on Frontend


---

## 📂 Access to Code  

The codebase for Akira is **private**.  
👉 If you’re interested in exploring or collaborating, feel free to **ping me separately**.  

---
