# **Building-and-Evaluating-Advanced-RAG**

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeyfoRhEXFykYI2q4xBgtGek5YYHhp41pZaA&usqp=CAU)

Advanced Retrieval-Augmented Generation (RAG) techniques are a set of methods that improve the accuracy and relevance of large language model (LLM) applications by combining traditional language models with external knowledge bases. RAG techniques can be used in a wide range of applications, including chatbots, question-answering systems, content-generation tools, healthcare, and finance. 

Advanced RAG techniques can help businesses that want to use generative AI by improving:

- Information density: From retrieved documents
- Information retrieval accuracy: For retrieved documents
- User query response quality: For user queries
- System efficiency: For underlying LLMs
  
Advanced RAG techniques can be categorized into pre-retrieval, retrieval, and post-retrieval optimizations. Some examples of advanced RAG techniques include:

- Pre-retrieval optimization: Sentence window retrieval
- Retrieval optimization: Hybrid search
- Post-retrieval optimization: Re-ranking

Advanced RAG can use pre-retrieval and post-retrieval strategies to improve retrieval quality. For example, RAG can supplement an LLM's training with a database of searchable articles that are similar to user queries. These articles can then be retrieved and passed to the LLM for completion. RAG can also use agents to equip LLMs with tools and tasks to enhance their capabilities. 

RAG can be more cost-efficient than fine-tuning because it uses existing data and doesn't require extensive training stages. Developers can also use RAG to more efficiently test and improve their chat applications by controlling and changing the LLM's information sources. 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjjjhU75Fd2Ht1X1OCMoBcCb9ZFkUgThsqwA&usqp=CAU)

Advanced RAG evaluation, or Retrieval Augmented Generation (RAG) evaluation, measures how well a RAG pipeline performs. RAG is a framework that uses a Large Language Model (LLM) to generate responses that are relevant to a user's context. RAG evaluation assesses how well the retrieval component of a RAG pipeline selects and ranks relevant data or documents. 

RAG evaluation can assess the following aspects of a RAG system:

- Faithfulness: How factual and consistent the answers are
- Answer relevance: How relevant the answers are to the prompt
- Context precision: Whether relevant chunks are ranked higher
- Aspect critique: How submissions are assessed based on predefined aspects like correctness and harmlessness
- Context recall: How well the ground truth and contexts are compared to check if all relevant information has been retrieved
- Context entities recall: How the number of entities in the retrieved context compares to the ground truth
- Context relevancy: How relevant the retrieved context is to the prompt
  
The RAGAS evaluation framework is one way to evaluate a RAG pipeline. It collects input, output, and context triplets to obtain metrics for different aspects of the pipeline. 


Some techniques that can enhance RAG include:

**Vector embedding length**

The length of the vector embeddings used to represent the input and retrieved information is a critical factor.

**Embedding metadata**

Embedding metadata along with the documents can help LLMs with additional context, resulting in improved generation.

**Using multiple search methods**

You can use keyword search, vector search, or structured queries, or even all three at the same time. 

You can learn more about advanced RAG techniques and building advanced RAG applications in courses on DeepLearning.AI's learning platform. 

