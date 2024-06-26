## App overview
   
At a conceptual level, the app's workflow remains impressively simple:
   
  1. The user uploads a document text file, asks a question, provides an OpenAI API key, and clicks "Submit."
      
  2. LangChain processes the two input elements. First, it splits the input document into chunks, creates embedding vectors, and stores them in the embeddings 
     database (i.e., the vector store). Then it applies the user-provided question to the Question Answering chain so that the LLM can answer the question:

  <img src="https://blog.streamlit.io/content/images/2023/06/LangChain-4-Conceptual-Overview-Simple.JPG.jpg" style="width: 100%;">

