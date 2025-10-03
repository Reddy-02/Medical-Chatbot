# Medical Chatbot 🤖💊

An AI-powered Medical Chatbot built as a **Jupyter Notebook** that provides symptom analysis, preliminary health guidance, and reliable medical information. It leverages **BioMistral-7B, embeddings, and vector stores (FAISS/Chroma)** to deliver **accurate, context-aware responses**.

## Features
- Symptom analysis & possible explanations
- Reliable medical knowledge retrieval
- 24/7 preliminary guidance
- Context-aware and accurate responses using LLM reasoning

## End-to-End Process
1. **Document Preprocessing & Chunking** – Large medical texts are broken into smaller, meaningful chunks for efficient model understanding and retrieval.  
2. **Embedding Creation** – Each chunk is converted into high-dimensional vectors capturing semantic meaning.  
3. **Vector Store (FAISS / Chroma)** – Embeddings are indexed in a vector database for fast, context-aware retrieval.  
4. **LLM Pipeline Integration** – **BioMistral-7B** is used with **LangChain** to generate context-aware responses by querying the vector store.  
5. **Final System** – A chatbot delivering accurate, medically relevant, and context-driven insights in real time.

## Tech Stack
- Language Model: BioMistral-7B  
- Pipeline: LangChain  
- Vector Store: FAISS / Chroma  
- Libraries: Hugging Face Transformers  
- Platform: Python (Jupyter Notebook)  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Reddy-02/Medical-Chatbot.git
2.Navigate to the notebook:
 cd Medical-Chatbot
3.Open Medical_Chatbot.ipynb in Jupyter Notebook or Google Colab.
4.Run all cells to start interacting with the chatbot.

What I Learned

Seeing chunking, embeddings, vector stores, and LLM reasoning come together to create a tangible healthcare solution was incredibly rewarding. This project reinforced how AI can bridge gaps in healthcare accessibility, providing quick, reliable guidance to those who need it most.

This experience strengthened my skills in LLMs, embeddings, LangChain, vector databases, and AI-driven knowledge retrieval, aligning with my vision of building practical, real-world AI solutions.

Contributing

Contributions are welcome! Open an issue or submit a pull request.
