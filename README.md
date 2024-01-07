# AIR-Project
## Project Overview
This information retrieval project focuses on improving the effectiveness of document retrieval.

## Methodology:
### 1. Dataset Analysis:
 - Thorough examination of the dataset to identify the most common topics.
 - Sentiment analysis: https://huggingface.co/docs/transformers/model_doc/distilbert)
 - The Train.jsonl dataset file is not uploaded due to its size, you can find it here: https://huggingface.co/datasets/BeIR/signal1m-generated-queries
### 2. BM25 Algorithm:
 - Utilization of the BM25 algorithm for the initial document retrieval.
 - Analyzing the performance of BM25 in capturing the relevance of documents to queries.
### 3. BERT Reranking:
 - Integration of BERT for reranking the documents retrieved by BM25.
 - This BERT model: is a sentence-transformers model. It maps sentences & paragraphs to a 768 dimensional dense vector space and can be used for tasks like clustering or semantic search. You can find it here: https://huggingface.co/sentence-transformers/bert-base-nli-mean-tokens consists
### 4. Query-Document Relationship Refinement:
 - Correction of inaccuracies in query-document assignments.
 - Ensuring that queries are appropriately matched with relevant documents.

