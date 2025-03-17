## 7. Retrieval Augmented Generation

**Building a RAG-powered Business Analyses System**

**Scenario:** Help a business analyst discover key information about a company from its available documents.

**Tasks:**

1. **Input**: Find and prepare a company's document on its financial report, blog post articles and press releases.
2. **Data Processing and Storing**: Process all documents, chunk and embed it properly into Milvus Vector store
3. **Answer Generation :** The analyst should be able to query related to information in the documents like revenue or domain and should be able to get a proper answer with the source of generation.

**Success Criteria**:

- The RAG model accurately identifies requirements from the Analyst and is able to return good responses.
- The RAG model effectively extracts relevant information from all the documents.
- **The sources returned should be correct and point to correct information.**
