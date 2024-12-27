
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

