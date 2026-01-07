# customer-support-rag-automation
This n8n workflow automates customer support by classifying incoming Gmail messages and generating RAG-based replies. It uses a LangChain text classifier to identify support queries, then employs a Gemini-powered AI Agent to retrieve relevant solutions from a Pinecone vector store. Validated responses are automatically sent as email replies.
