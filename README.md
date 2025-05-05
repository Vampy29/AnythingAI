# 🤖 AnythingAI

**AnythingAI** is an AI-powered Android app that lets users ask any question and receive intelligent responses. It uses a Python backend with a vector database for document retrieval and a question-answering model (like HuggingFace Transformers), and a frontend built with Jetpack Compose.

## 🚀 Features

- Ask natural language questions
- Answers powered by an AI model (SQuAD2.0 + vector retrieval)
- Android UI with Jetpack Compose
- Typing animation for responses
- App icon customization
- Local & remote image/gif support
- GitHub-integrated build and deployment

---

## 📱 Android App

- Built with Kotlin + Jetpack Compose
- Uses Retrofit to connect to the backend
- Material 3 UI
- Live preview and dark/light theme support
- Supports animated gifs and local images

## 🧠 Backend (Python)

- FastAPI server with `/ask` route
- HuggingFace Transformers (`deepset/roberta-base-squad2`)
- Vector index using LlamaIndex + LangChain
- Embedding with `sentence-transformers/all-MiniLM-L6-v2`
- File-based document indexing (`/data` directory)

---

## 🛠 Tech Stack

- **Frontend:** Android Studio, Jetpack Compose, Kotlin
- **Backend:** Python, FastAPI, HuggingFace, LlamaIndex
- **AI Models:** RoBERTa (SQuAD), MiniLM for embeddings
- **Other:** GitHub, Gradle, Retrofit, Coil (image loading)
