# Serene - AI-Powered Mental Health Chatbot

**Serene** is an innovative mental health chatbot designed to provide personalized support for students and working professionals. Developed for the **Google GenAI Hackathon**, Serene focuses on delivering empathetic, real-time conversations to help users navigate stress, anxiety, and emotional challenges. Our goal is to complement professional mental health services by offering accessible self-help resources.

## 🌿 Overview

Serene processes user queries with a **hybrid search system** that combines **LangChain** and **ChromaDB** to understand both context and emotion. Powered by **Gemini 1.5 Flash** and the **Retrieval-Augmented Generation (RAG)** architecture, Serene delivers relevant, research-backed responses tailored to users' needs. Additionally, it offers mindfulness exercises, stress management tips, and referrals to professional mental health services when necessary.

## 💡 Key Features

- **Personalized Chat Interactions:**  
  Engage in real-time, empathetic conversations tailored to user input and emotional state.
  
- **Context-Aware Responses:**  
  Understands the user's emotional tone and context to provide more accurate, meaningful responses.

- **Robust Knowledge Base:**  
  Pulls from mental health research, expert opinions, and coping strategies to provide reliable support.

- **Mindfulness Exercises & Self-Help Tips:**  
  Offers stress management techniques, breathing exercises, and mindfulness practices to promote well-being.

- **Referrals to Professional Support:**  
  Directs users to professional services when necessary, ensuring a balance between self-help and professional guidance.

## 🚫 Out of Scope

- **No Medical Diagnoses or Treatment Plans:**  
  Serene does not provide medical advice, diagnoses, or treatment and is designed to complement, not replace, professional mental health services.

- **Not for Emergency Crises:**  
  Serene does not handle severe mental health crises. Users are directed to emergency services when required.

## 🚀 Challenges We Faced

1. **Library and Dependency Conflicts:**  
   Balancing library versions (Generative AI, LlamaIndex, Langchain, VectorDB) posed challenges. We resolved this by using containerized setups with virtual environments to isolate dependencies.

2. **Emotion Recognition:**  
   Capturing nuances like sarcasm, irony, and subtle emotions was a challenge. We implemented a **multimodal emotion detection** system to enhance accuracy in text-based emotional responses.

3. **Scalability:**  
   Deploying large models on freely available resources required balancing performance with cost-efficiency. We optimized model deployment for scalability with limited global resources.

## 📚 Tech Stack

### App:
- **Kotlin** (Frontend)
- **Firebase** (Backend & Real-time Database)

### Website:
- **Flask** (Web Framework)
- **Hugging Face** (For NLP Models)
- **ChromaDB** (For Vector Database & Search)
- **LangChain** (Context-aware responses and retrieval)
- **LlamaIndex** (Knowledge Graph for enhanced search)

## ✨ Future Enhancements

- **Multilingual Support:**  
  Expanding Serene's language capabilities to cater to a more diverse audience.

- **Mood Tracking:**  
  Adding features to track users' moods over time and offer personalized insights.

- **Professional Partnerships:**  
  Collaborating with licensed mental health professionals to provide more comprehensive support.

- **Community Forums:**  
  Building a community space where users can share experiences, ask questions, and receive peer support.

## 👨‍💻 Team

- **Azad Kumar Jha**
- **Harsh Gupta**
- **Prince Maurya**
- **Rishit Rastogi**

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/serene-mental-health-bot.git
   Navigate to the project directory:

bash
Copy code
cd serene-mental-health-bot
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Set up your environment variables for API keys and database settings in a .env file.

Run the Flask application:

bash
Copy code
flask run
📑 Requirements
text
Copy code
firebase-admin
langchain
chromadb
llamaindex
huggingface-hub
python-dotenv
kotlin
flask
```
