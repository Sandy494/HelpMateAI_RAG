MrHelpMateAI_RAG

**Overview:**
to build a robust generative search system capable of effectively and accurately answering questions from a policy document. 

**Project Structure:**
1. Embedding Layer:   Explore various PDF document processing and chunking strategies.   Choose between OpenAI's embedding model or SentenceTransformers for vector representations.



2. Search Layer:   Design three diverse queries reflecting potential user questions in policy documents.   Implement vector database searches against ChromaDB, incorporating a cache mechanism.   Enhance search results with a re-ranking block using cross-encoding models from HuggingFace.


Rerank after cross encoding provided


3. Generation Layer:   Design an exhaustive and instructive prompt for the Language Model (LM) to ensure coherent answer generation.Provide a few-shot example in the prompt to improve LM output.

   

