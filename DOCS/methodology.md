Methodology
 1. Data Collection

A structured FAQ dataset was created containing restaurant-related questions and answers including menu details, policies, timings, and reservation information.

 2. Data Preprocessing

- Text cleaning
- Lowercasing
- Removal of unnecessary characters
- Formatting into structured JSON format

 3. Embedding Generation

- Questions and documents converted into vector embeddings.
- Stored in a vector database for semantic search.

 4. Retrieval Process

- User query converted into embedding.
- Similar documents retrieved using cosine similarity.

 5. Response Generation

- Retrieved context passed to LLM.
- LLM generates natural and relevant answer.

---

## 6. Testing & Evaluation

- Tested with common restaurant-related queries.
- Evaluated based on response accuracy and relevance.
