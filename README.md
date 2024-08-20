# Hybrid Search Model for Tabular Data
This project implements a hybrid search model that combines semantic search and fuzzy logic to match user queries against tabular data stored in an Excel file. The model utilizes the SentenceTransformer library for generating embeddings and fuzzywuzzy for fuzzy string matching, providing a robust solution for data retrieval tasks.

## Features
1) Hybrid Search: Combines semantic similarity (using sentence embeddings) and fuzzy string matching for enhanced search capabilities.
2) Batch Processing: Efficiently processes large datasets by encoding data in batches.
3) Modular Codebase: The code is modular, making it easy to maintain and extend.
4) Customizable: Easily adjustable to handle different file formats and query types.

## Universal Sentence Encoder (USE)

- **Overview**: The Universal Sentence Encoder (USE) is a state-of-the-art model developed by Google for encoding sentences, phrases, or paragraphs into fixed-length vectors (embeddings). These embeddings capture the semantic meaning of the text and can be used in various natural language processing (NLP) tasks, including text classification, clustering, semantic search, and more.

- **Key Features**:
  - **Semantic Understanding**: USE generates embeddings that reflect the semantic meaning of the text, allowing it to understand context beyond simple keyword matching.
  - **Versatility**: Suitable for a wide range of applications, including semantic search, question answering, and text similarity.
  - **Pre-trained Models**: USE comes in several variants, including models optimized for different tasks and trade-offs between accuracy and computational efficiency.
  - **Multi-language Support**: Some versions of USE support multiple languages, making it a robust tool for global applications.

- **Applications**:
  - **Semantic Search**: USE embeddings can be leveraged to improve search relevance by understanding the intent and context behind user queries.
  - **Text Classification**: USE embeddings can serve as input features to classifiers, boosting the performance of models in tasks like sentiment analysis or topic categorization.
  - **Text Similarity and Clustering**: By converting text to embeddings, USE allows for efficient computation of similarity scores between texts, useful for clustering or deduplication tasks.

- **How USE Integrates with This Project**:
  - The combination of USE with fuzzy logic in the hybrid model allows for a robust search experience, handling both semantically similar queries and those with slight typographical errors or variations.

- **Advantages of Using USE**:
  - **Fast and Scalable**: USE is designed to provide high-quality embeddings quickly, making it suitable for large-scale applications.
  - **Pre-trained and Ready to Use**: With pre-trained models available, you can quickly integrate USE into your applications without the need for extensive training data or resources.
  - **Community Support and Documentation**: Being developed by Google, USE is well-documented and supported by a large community, with numerous resources available for troubleshooting and optimization.

## Requirements
* Visual Studio Code
* Python 3.11.9
* Pandas
* Sentence Transformers
* FuzzyWuzzy
* NumPy
* Time