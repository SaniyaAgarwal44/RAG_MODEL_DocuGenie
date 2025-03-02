## RAG Q&A Chatbot using OpenAI, LangChain, FAISS and Gradio
Retrieval-Augmented Generation(RAG) emerges as a promising approach that handles the limitations of Large Language Models(LLMs) mainly hallucinating information and inconsistent outputs. Using RAG, we can give the model access to specific information that can be used by the model as context to generate responses that are more factually correct and more consistent.

## OBJECTIVE 👩‍🏫

DocuGenie is an advanced Document Reader Chatbot that leverages the power of Retrieval-Augmented Generation (RAG) to provide accurate, context-aware responses based on uploaded documents. This project is designed to efficiently process and understand textual data, enabling users to query documents conversationally and retrieve relevant insights with precision.

With DocuGenie, users can:

* #### Upload various document formats (PDF, TXT, DOCX, etc.).
* #### Ask questions about the content in natural language.
* #### Receive intelligent, context-aware responses backed by RAG.
* #### Benefit from efficient information retrieval without manually searching through documents.

This project showcases the fusion of NLP, LLMs, and vector-based retrieval to create a seamless and interactive document-reading experience. 🚀

## What is Gradio ? 🤔

Gradio is an open source Python library that simplifies the process of creating user interfaces for ML models, APIs, etc. In just a few lines of code, we can build a web interface that allows people to interact with the model.

## RAG PIPELINE: 

When a user queries a document, the pipeline first retrieves the most relevant text chunks using vector embeddings and similarity search. These retrieved segments are then passed to a language model, which generates a contextually aware response. This approach ensures that answers are both precise and grounded in the uploaded content, reducing hallucinations and improving the chatbot’s reliability. 🚀

![Image](https://github.com/user-attachments/assets/37ef1907-9462-40a7-801c-9a06c6608633)

## USER INTERFACE 🤖

           
![Image](https://github.com/user-attachments/assets/8131362e-04ca-4c62-b34a-4c57932e259f)
![Image](https://github.com/user-attachments/assets/750f2a5c-2b0d-4a33-8522-69a5a9b2ee06)
![Image](https://github.com/user-attachments/assets/3721e400-be55-4ce6-8289-78ee1a42d901)


### 🚀 Closing Note

Thank you for exploring DocuGenie! 📄🤖

 Designed to make document interaction effortless, DocuGenie bridges the gap between static text and intelligent insights. Whether you're searching for specific details or summarizing content, this AI-powered assistant ensures seamless, context-aware responses. Keep innovating, keep exploring, and let DocuGenie handle the reading while you focus on what matters! ✨📚
