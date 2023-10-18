## Problem Statement:

The problem is to develop a generative AI chatbot that leverages LangChain technology, incorporating the LLM (Large Language Model) to create a conversational agent capable of engaging in natural, contextually relevant, and coherent conversations with users. This chat bot is capable of providing you the best response related to your healthy life style. The goal is to provide an intelligent chatbot solution that can understand user queries, generate human-like responses, and adapt to different conversational styles, languages, and specialized domains.

**Tools Used:**
-  Python
- Flask
- OpenAI
- LLM
- Langchain
- Vector database- FAISS
- PyPDF2

Details of Generative AI Chatbot Using LangChain and LLM Model:

1. **Introduction:**
   Developing a generative AI chatbot is a challenging task that involves combining advanced language models like the LLM with innovative technologies such as LangChain. The chatbot aims to assist users, answer questions, provide recommendations, and engage in meaningful dialogues.


2. **LangChain Technology:**
   - LangChain is a blockchain-based technology designed to improve the efficiency, security, and scalability of natural language processing (NLP) tasks.
   - It ensures data privacy, decentralization, and the ability to build and deploy AI models in a collaborative and secure manner.


3. **LLM Model Integration:**
   - The LLM model, which is a state-of-the-art AI model, is the core of the chatbot's natural language understanding and generation capabilities.
   - The model should be fine-tuned for chatbot applications to adapt to specific tasks and domains.
   - Model used: "gpt-3.5-turbo"


4. **Key Components:**
   - **User Interface:** Develop a user-friendly interface where users can interact with the chatbot through text.
   - **Parsing:** From Langchain library we have used, **CharacterTextSplitter** class. It takes the content of a document and splits it by the default separator(\n\n) which is the first level of chunking.
   - **Embeddings:** Using OpenAIEmbeddings class and vector data base FAISS, embedding of the context are created which are in chunks forms.
   - **Response Generation:** Use the LLM model to generate contextually appropriate responses. Ensure that responses are coherent, relevant, and human-like.
   - **Context Management:** Implement context tracking to maintain a coherent conversation, remembering previous interactions and tracking all the calls.
   - **Domain Specialization:** Fine-tune the model for health care to provide accurate responses.


5. **Training and Data:**
   - Train the LLM model on a diverse dataset, including dialogues, to enable it to handle a wide range of conversations.
   - Curate domain-specific datasets and fine-tune the model to excel in specialized areas.
   - Here the domain is Healthcare

6. **Evaluation and Metrics:**
   - Establish evaluation metrics, including accuracy, fluency, context coherence, and user satisfaction.
   - Continuously monitor and improve the chatbot's performance using user feedback.

7. **API:**
   - Flask framework used for building the api and teste in postman.
