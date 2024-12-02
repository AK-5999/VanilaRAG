# VanilaRAG
A vanilla RAG (Retriever-Augmented Generation) pipeline retrieves relevant documents and generates responses by combining retrieval and generation models.


A basic RAG (Retriever-Augmented Generation) pipeline combines two main components: a retriever and a generator. Here are the basic steps:

1. **Retriever**: Given an input query, the retriever searches a large database of documents or knowledge sources. It identifies and selects the most relevant documents or passages based on their similarity to the query.

2. **Generation**: The selected documents are then passed to the generator (usually a language model). The generator uses the information in the retrieved documents along with the query to generate a coherent and informative response.

The key idea is to improve the quality of the response by combining the retrieval of relevant data with the generative power of language models, resulting in more accurate and contextually relevant answers.
