

## 1. Mathematics for ML

### **Movie Recommendation with User Preferences**

**Scenario:** You're building a movie recommendation system. Users can rate movies on a scale of 1 (dislike) to 5 (like). Your goal is to create a system that recommends movies to users based on their preferences.

**Tasks:**

**1. Data Representation:**

1. Represent each user as a vector where each element corresponds to a movie genre. Initialize all elements to 0.
2. For each movie rating by a user, update the corresponding genre element in their vector by the rating value.

**2. Recommendation:**

1. Define a function to recommend movies for a user. This function can take the user's preference vector (or the PCA-reduced version) and a list of movies with genre information as input.
2. Calculate a similarity score between the user's preference vector and the genre vector of each movie (e.g., using dot product).
3. Recommend movies with the highest similarity scores to the user.

**DataSet:**

[movie_ratings](https://docs.google.com/spreadsheets/d/17a4O9KdJGm_NMJ6y6wfBOG6GJD1ymBus3U1I4tCaHDE/edit?usp=sharing)
