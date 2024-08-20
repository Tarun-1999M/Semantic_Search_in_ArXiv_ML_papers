# **Semantic Search in ArXiv ML Papers**

This project implements a semantic search application using a dataset of Machine Learning papers from ArXiv. The dataset is tagged with "cs.LG" to indicate relevance to Machine Learning, and contains approximately 100,000 papers. These papers are a subset filtered from the full ArXiv dataset, which originally contained about 2 million papers.

## **Overview**

The objective of this project is to build an efficient search system that retrieves relevant papers based on a user's query. By leveraging the power of Natural Language Processing (NLP) and embedding techniques, the system is designed to understand the semantic meaning behind user queries and match them with the most relevant papers in the dataset.

## **Demo**

<a href="https://huggingface.co/spaces/Tarun-1999M/Semantic_Search_in_ArXiv_ML_Papers" target="_blank">Click here to view the live demo</a>.

## **How It Works**

The interface is built using Gradio, allowing users to input text and receive predictions for the most relevant papers. The model returns the paper titles, abstracts, and similarity scores, helping researchers quickly find the papers they need.

## **Features**

- **Semantic Search**: Search for papers based on the semantic meaning of your query.
- **Efficient Indexing**: Uses FAISS for fast, scalable similarity search.
- **Interactive Interface**: Powered by Gradio for an easy-to-use experience.
- **Hugging Face Integration**: Leverages pre-trained models from Hugging Face.

## **Setup**

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tarun-1999M/Semantic_Search_in_ArXiv_ML_Papers.git
   cd Semantic_Search_in_ArXiv_ML_Papers
