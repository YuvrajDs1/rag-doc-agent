### 📊 Stock Market RAG Agent (2024)

An AI-powered Retrieval-Augmented Generation (RAG) agent built with LangChain, LangGraph, Chroma, and Groq LLaMA 3.1.

The agent can answer questions about stock market performance in 2024 by retrieving information from a PDF knowledge base and combining it with reasoning from an LLM.

#### ✨ Features

📄 PDF ingestion → Reads and processes the Stock_Market_Performance_2024.pdf.

🧩 Text splitting → Splits text into semantic chunks for better retrieval.

🔍 Vector search → Stores and queries embeddings using ChromaDB.

🛠 Tool-augmented reasoning → LLM decides when to call a retriever tool.

🧠 Agent graph → Built with LangGraph StateGraph to manage reasoning steps.

🚀 Groq-powered LLaMA 3.1 → Fast and efficient inference.

📌 Cited answers → Always references the source document for transparency
