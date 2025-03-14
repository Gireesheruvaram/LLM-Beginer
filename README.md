
Kata 1: Storing and Querying Embeddings
Objective: Learn how to store embeddings in a vector database and query it using cosine similarity.
Task:
Install a vector database library like Pinecone, Weaviate, or FAISS.
Generate embeddings from a set of text documents using an LLM (e.g., OpenAI's API or Hugging Face models).
Store the generated embeddings in the vector database.
Perform a query on the vector database by converting a query text into its embedding and finding the closest matches using cosine similarity.
Steps:
Install necessary packages and initialize the vector database.
Create embeddings using an LLM.
Insert embeddings into the vector database.
Implement a cosine similarity search and return the top N closest documents.
Expected Outcome:
A function that accepts a query and returns the most relevant documents based on vector similarity.

Kata 3: Building a Contextual LLM Application with Vector Database
Objective: Create a contextual chatbot that uses a vector database to retrieve relevant information from a document corpus.
Task:
Build a basic chatbot that uses a vector database to retrieve relevant information based on user input.
The chatbot should retrieve similar documents from a preloaded knowledge base (corpus) and present them as responses.
Fine-tune the LLM's responses based on the retrieved documents.
Steps:
Preprocess a document corpus by generating embeddings using an LLM.
Store these embeddings in the vector database.
Implement a chatbot interface where user input is embedded and used to query the vector database for relevant documents.
Use the retrieved documents to generate or enhance the chatbot's response.
Expected Outcome:
A chatbot that can understand user queries and provide relevant responses using the content of the preloaded document corpus.

