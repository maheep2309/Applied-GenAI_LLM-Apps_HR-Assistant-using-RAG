# Applied-GenAI_LLM-Apps_HR-Assistant-using-RAG
An AI-powered HR assistant designed to answer employee queries by leveraging organizational policy documents. The solution uses document processing, vector search, and conversational AI to deliver accurate, context-aware responses through an interactive chatbot interface.

# Project Summary
The AI-Powered HR Assistant project is a conversational chatbot developed to improve HR operations at Nestlé by enabling employees to access HR policy information quickly and efficiently through natural language queries. Built using a Retrieval-Augmented Generation (RAG) architecture, the system processes HR policy PDF documents using PyPDFLoader, converts the extracted text into embeddings, and stores them in ChromaDB for semantic search and retrieval. The chatbot integrates OpenAI’s GPT-3.5 Turbo model to generate accurate, contextual, and conversational responses, while guardrails are implemented to reduce hallucinations, enforce factual answers, and block unsafe queries. The solution also includes multiple retrievers, including an internal HR policy retriever and a fallback web search retriever, ensuring reliable information retrieval. An interactive Gradio-based user interface allows seamless employee interaction, and ROUGE evaluation metrics are used to assess response quality and retrieval effectiveness. Overall, the project showcases how Generative AI and Agentic AI techniques can streamline enterprise HR support, improve operational efficiency, and deliver scalable AI-powered assistance.

Agentic AI Concepts / Topics Covered: -
- Retrieval-Augmented Generation (RAG)
- Agentic Workflow Orchestration
- Multi-Retriever Architecture
- Semantic Search & Similarity Retrieval
- Vector Embeddings & ChromaDB
- Context-Aware Response Generation
- Autonomous Retrieval Decision Making
- Fallback Retrieval Mechanisms
- AI Guardrails & Safety Controls
- Hallucination Prevention Techniques
- Prompt Engineering
- LLM Integration with GPT-3.5 Turbo
- Document Processing & Text Chunking
- Response Evaluation using ROUGE Metrics
- Human-AI Interaction using Gradio UI
