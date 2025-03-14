## 3. Natural Language Processing

Problem 1

**Text Cleaning Pipeline**

**Scenario:** You're building a basic sentiment analysis tool for social media comments. The comments often contain typos, emojis, and irrelevant words. You need to clean the text before feeding it to your sentiment analysis model.

**Tasks:**

1. **Text normalization:** Write a function that takes a comment string and performs the following:
    - Lowercase all characters.
    - Remove punctuation (except for exclamation points and question marks that might be sentiment indicators).
    - Replace emojis with descriptive text (e.g., "happy" for ).
2. **Tokenization:** Write a function that splits the normalized text into individual words (tokens).
3. **Stop word removal:** Create a list of common stop words (e.g., "the", "a", "is"). Write a function that removes these stop words from the list of tokens.

