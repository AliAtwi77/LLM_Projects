# **Overview**

This project is a Retrieval-Augmented Generation (RAG) chatbot that allows users to upload multiple PDF documents and chat with them using a Large Language Model (LLM). It efficiently retrieves relevant information from the uploaded PDFs and generates meaningful responses.

# **Features**

📄 Multi-PDF Support: Upload multiple PDFs for context-aware conversations.

🔍 Retrieval-Augmented Generation (RAG): Ensures responses are backed by relevant document content.

🤖 LLM Integration: Utilizes a powerful language model for natural language understanding and response generation.

⚡ Efficient Chunking & Embeddings: Splits PDF text into meaningful chunks and indexes them for fast retrieval.

🔎 Similarity Search: Uses cosine similarity with FAISS to retrieve the most relevant document sections.

🌐 Web Interface: A simple and interactive chat UI for seamless user experience.


# **Installation**
`# Clone the repository`

`git clone https://github.com/AliAtwi77/LLM_Projects.git`

`# Install dependencies in a virtual environment`

`pip install -r requirements.txt`


# **Environment Variables (.env File)**
This project requires certain environment variables to be set in a .env file. Create a .env file in the root directory and add the following variables:

`GOOGLE_API_KEY=your_google_api_key`

if you like to use the Google api visit this website:([Google_API](https://ai.google.dev/gemini-api/docs/api-key)) 

# **Usage**
1.Go to the MultiPdfDirectory

`cd MultiPdfDirectory`

2.Start the application(in cmd type:)

`streamlit run app.py`

3.Upload PDFs through the web interface and press Process.

4.Chat with your documents!
