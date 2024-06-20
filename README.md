# LlamaIndex-And-Qdrant-QA-System-With-Recency-And-Cohere-Reranking-Updates
LlamaIndex and Qdrant News Article Q&amp;A App With Recency and Cohere Reranking Postprocessing
A news article was downloaded and a Q&A bot was built with Qdrant and LlamaIndex.
A Recency posprocessor, Cohere Reranking postprocessor, and a combined Recency plus Cohere Reranking postprocessors were added.
The Recency postprocessor may not be a good choice if data from a specific year is needed as the Recency postprocessor was unable to answer those questions.
OpenAI answered questions from it's general world knowledge when the data was not available from  the vector store.
