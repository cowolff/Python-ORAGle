# Python ORAGle: Using documentation as a knowledge base for programming questions
In this project we used retrieval augmented generation in combination with the Gemma-7b-it model to create a question answering LLM for python related problems. To achieve this, we relied on 3 core components:
- Online Documentation and Tutorials in a PDF format as a knowledge base
- ChromaDB as a vector database with gte-large (based on googles BERT-framework) as its embedding model
- Gemma-7b-it as a LLM
<br/>

We furthermore provide an automated benchmark to evaluate the retrieval quality for the specific database, again relying on Gemma-7b-it as a core component of this benchmark.
