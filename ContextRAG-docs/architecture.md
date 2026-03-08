# ContextRAG Architecture

ContextRAG uses Retrieval Augmented Generation (RAG) to extend LLM context.

The architecture includes:

User
↓
Custom UI
↓
Java RAG Service
↓
Embedding Model
↓
Vector Database (Weaviate)
↓
Context Retrieval
↓
Prompt Construction
↓
LLM
↓
Response

Conversation memory and knowledge ingestion operate through Kafka pipelines.