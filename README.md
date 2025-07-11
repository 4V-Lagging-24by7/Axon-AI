# 🌐 Axon AI: Multi-Agent Fitness Assistant
Personalized workout and nutrition guidance using LangFlow, Streamlit, RAG, and OpenAI

## 📌 Overview
Axon AI is a multi-agent fitness assistant built using LangFlow to route user queries to specialized agents like fitness and nutrition. It leverages Retrieval-Augmented Generation (RAG) with vector embeddings stored in Astra DB to generate highly contextual and personalized responses. The system is deployed via an intuitive Streamlit interface that allows users to input fitness goals, take notes, and interact with intelligent agents in real-time.

## 🎥 Demo Video
Watch on YouTube

## 🚀 Features
- 🧠 Multi-agent routing using LangFlow for specialized query handling
- 🗂️ RAG pipeline with Astra DB for context-aware responses
- 💬 Streamlit UI for real-time chat, data entry, and goal tracking
- 🔄 Integrated OpenAI prompts and flows via LangFlow canvas

## 🛠️ Tech Stack
- **Frontend:** Streamlit
- **LLMs & Agents:** OpenAI API, LangFlow, LangChain
- **Database:** Astra DB (Vector store)
- **Backend:** Python
- **Other Tools:** REST APIs, FAISS-like vector search

## 📂 Project Structure
| File/Folder   | Description                   |
|---------------|-------------------------------|
| app.py        | Streamlit UI logic            |
| flows/        | LangFlow flow definitions     |
| agents/       | Specialized agent logic       |
| vector_store/ | Astra DB setup                |
| data/         | Sample user notes/profiles    |
| .env          | Environment variables         |

## 🔧 Setup Instructions
1. Clone the repository  
2. Install dependencies  
3. Add `.env` with OpenAI and Astra DB API keys  
4. Run with:


## 📚 Concepts Used
- LangFlow for LLM agent orchestration
- Retrieval-Augmented Generation (RAG) for grounded answers
- Astra DB for vector embeddings and semantic search
- Streamlit for clean interface and user interaction

## 🧠 Future Enhancements
- User authentication
- Goal and meal planner
- Progress tracking dashboard
- Feedback-based agent refinement

## 🤝 Contributions
Open to contributions! Feel free to submit issues or PRs to enhance flows, UI, or logic.

## 📄 License
MIT License

## 📬 Contact
Charvi Singh  
📧 charvis2019@gmail.com  
🔗 LinkedIn

