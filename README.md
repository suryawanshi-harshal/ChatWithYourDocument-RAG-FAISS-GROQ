# Chat with your document

This project is a document-based Q&A chatbot that uses Retrieval-Augmented Generation (RAG) to answer questions based on the content of provided documents. The chatbot leverages the Groq API with the Mixtral model for natural language understanding and generation. It currently only supports .pdf and .docx files.

## Tech Stack

- **Document Processing**: PyPDFLoader, UnstructuredWordDocumentLoader
- **Text Splitting**: Langchain's RecursiveCharacterTextSplitter
- **Embeddings**: Sentence Transformers (`all-mpnet-base-v2`)
- **Vector Store**: FAISS (Facebook AI Similarity Search)
- **Language Model**: Groq API with Mixtral model (`mixtral-8x7b-32768`)
- **Conversational Chain**: Langchain's ConversationalRetrievalChain
- **Prompt Template**: Langchain's ChatPromptTemplate

Set your Groq API key:
  - Create an account on https://console.groq.com
  - Under API Keys section create your key.


