# Retrieval Augmented Generation (RAG)

RAG improves LLM responses by retrieving external knowledge.

Architecture:

User Question
↓
Embedding model converts query into vector
↓
Vector database search
↓
Relevant documents retrieved
↓
Context provided to LLM
↓
LLM generates answer

Advantages:

• Reduces hallucinations
• Uses private data
• Improves accuracy

Typical stack:

Embedding Model: OpenAI / BGE  
Vector DB: FAISS / Pinecone  
LLM: GPT / Claude
