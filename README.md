# Project_llm_chatbot.
# LLM-Based Intelligent Chatbot  An **LLM-powered intelligent chatbot** built using **Python, Flask, Retrieval-Augmented Generation (RAG), ChromaDB, and Ollama**. The project allows users to interact with uploaded documents and receive **context-aware, intelligent responses** using a local LLM pipeline.  ---


🚀 Features
💬 Interactive chatbot interface with Flask
📄 Document upload and processing
🔍 Retrieval-Augmented Generation (RAG)
🧠 Context-aware answers using vector search
🤖 Local LLM integration with Ollama
🗂️ Modular prompt management
🎨 Simple chatbot UI prototype
📘 Developer guide included for easy extension
🛠️ Tech Stack
Python 3.x
Flask
Ollama
ChromaDB
PyPDF2 / document loaders
HTML, CSS, JavaScript
WSL / Ubuntu
📁 Project Structure
llm-based-intelligent-chatbot/
│── app.py
│── document_loader.py
│── file_handler.py
│── greeting_handler.py
│── llm_rag.py
│── query_classifier.py
│── rag_pipeline.py
│── requirements.txt
│── developer_guide.md
│── .gitignore
│── templates/
│── chatbot_dummy_ui/
│── modules_prompt/
⚙️ Installation & Setup
1) Clone the repository
git clone https://github.com/sourabhsk24/project_llm_chatbot.git
cd llm-based-intelligent-chatbot
2) Create virtual environment
python3 -m venv venv
source venv/bin/activate
3) Install dependencies
pip install -r requirements.txt
4) Run Ollama model
Make sure Ollama is installed and the required model is available:

ollama run llama3
5) Start the Flask app
python app.py
▶️ Usage
Start the Flask server
Open the chatbot UI in browser
Upload sample PDF/documents
Ask questions based on uploaded content
Receive context-aware AI responses
🎯 Use Cases
📚 PDF-based question answering
🎓 Student academic assistant
📄 Knowledge base chatbot
🏢 Internal document search bot
🤖 Local LLM experimentation project
🔮 Future Enhancements
Multi-document querying
Conversation memory
User authentication
Cloud deployment
Better UI/UX
Support for multiple LLMs
👨‍💻 Author
Shaaz Makthumbade Aspiring Python / AI Developer
