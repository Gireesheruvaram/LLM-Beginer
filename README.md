## 6. Vector Storage

**Building a Movie Recommendation System with Chroma Vector DB**

**Scenario:** Develop a Python script that utilizes Chroma Vector DB to create a movie recommendation system based on user preferences via query and movie descriptions.

**Tasks:**

1. For each movie, extract the description text.
2. Use any embedding_model to generate an embedding for the description.
3. Insert the movie description, its embedding, and the metadata (genre and director) into the ChromaDB collection
4. Based on the user query form a proper filter expression.
5. Retrieve the top 5 results based on the user query.

**Dataset:**

[**Movies Dataset**](https://docs.google.com/spreadsheets/d/17zn3h5pDWTz1CEiouAc0c5KWpobk7OFg8D0wmO6QJoE/edit?usp=sharing)
