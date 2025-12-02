# 🚀 RAG Pipeline with Ollama, Groq LLM & Astra DB (Cassandra)
Bu proje; Ollama, Groq LLM, LangChain, ve Astra DB (Cassandra) kullanılarak inşa edilmiş, uçtan uca çalışan yüksek performanslı bir Retrieval-Augmented Generation (RAG) sistemidir.
Web’den içerik toplar, metni embed eder, vektör veritabanında indeksler ve gerçek-zamanlı sorgulara optimize yanıtlar üretir.

## 🧩 Özellikler
* Ollama (llama3.2:3b) ile yerel embedding üretimi
* Groq LLM (Mixtral / LLaMA-3) ile ultra hızlı inference
* Astra DB (Cassandra) Vector Store entegrasyonu
* LangChain tabanlı modern RAG pipeline
* Web kaynaklarından dinamik veri çekme & chunking
* Gerçek zamanlı sohbet modu (CLI Chatbot)
* Kolay deploy ve yeniden kullanılabilir modüler yapı

## 🏗️ Mimari Bileşenler
* WebBaseLoader → Web scraping
* RecursiveCharacterTextSplitter → Chunking
* OllamaEmbeddings → Vektör embedding üretimi
* Cassandra VectorStore → Vektörlerin persist edilmesi
* Retriever → Semantic search
* LLM Document Chain → Context-aware metin sentezi
* RAG Pipeline → Retrieval + Generation
