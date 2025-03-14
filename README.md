### Problem 2

**Document Summarization**

**Scenario**: You're working on a news aggregator that displays summaries of various articles. You want to identify the most important keywords in each article to generate concise summaries.

**Tasks:**

1. **TF-IDF calculation**: Implement the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm. This involves calculating the frequency of each word in a document (TF) and how rare it is across all documents (IDF).
2. **Document Summarization**: Write a function that takes a list of pre-processed news articles (cleaned text) as input. It should perform the following:
    - Calculate TF-IDF for each word in each document.
    - Identify the top N words (keywords) with the highest TF-IDF scores for each document.
    - Generate a summary sentence using these keywords.

