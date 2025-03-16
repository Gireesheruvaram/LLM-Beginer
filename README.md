x<<<<<<< HEAD
## 5. Prompt Engineering DRAFT

### Problem 1

Your task is to design a system, given a generic question about a company's data, performs two main functions through prompt engineering with a Large Language Model (LLM):

1. Transforms the generic question into a detailed, context-specific question. This involves identifying the relevant company and aspects of the query that need specificity. The output should be a JSON object containing the refined question and the name of the targeted database.
2. Generates an accurate SQL query based on the refined question and the specified database schema. This SQL query should be capable of retrieving the relevant data from the database.

Deliverables:

- A document detailing the prompts used for both stages of the process, including the rationale behind the prompt design and any iterations or refinements made.
- Examples of generic questions, the JSON outputs generated from these questions, and the final SQL queries produced.
- A brief analysis of the system's effectiveness, including any challenges encountered in guiding the LLM to produce accurate and relevant outputs at both stages.
=======


Kata 3: Retrieval-Augmented Generation (RAG) using LangChain
Objective: Build a knowledge-enhanced LLM by integrating LangChain's document retrieval capabilities.
Task:
Use LangChain’s retrieval tools to augment a language model's capabilities by retrieving relevant information from a document store.
The model should be able to answer questions by querying a local or external database or knowledge base.
Steps:
Set up a document store (e.g., using Pinecone, Weaviate, FAISS, or another vector database).
Implement LangChain’s document retrieval functionality.
Connect the LLM to retrieve documents based on user queries and use the retrieved information to generate contextually accurate responses.
Expected Outcome:
A system where the LLM pulls relevant documents or facts from a database to enhance its responses with factual information, mimicking a knowledge-augmented chatbot.
>>>>>>> 45f96449da563fd70e8e410bc877df0f1132d05b
