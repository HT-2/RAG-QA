# RAG-QA
A question answering system based on Retrieval Augmentation Generation model
The need for an information retrieval system becomes more than important to uncover hidden
trends and insights in large volumes of unstructured data. Question-answering systems have
evolved significantly in the past few months with new generation large language models and
transformer-based language models. This project aims to develop a question-answering system
that could contribute to knowledge discovery by extracting meaningful patterns and relationships
from data. Generally speaking, two types of language models are extractive and generative.
Extractive models directly extract text from the documents and the context to answer the
question. On the contrary, generative models can generate a whole new answer from scratch,
which is more natural and fluent than extractive models. However, these models are prone to
hallucinations, a tendency to make things up when data is insufficient or lacks context.
Retrieval augmentation models have emerged to harness the strengths of both the extractive and
generative models. The RAG systems combine the information extraction component from the
extractive models and the generators from the generative models. The information retrieval
module identifies the most relevant documents from the knowledge base and provides factual
context. The generative model uses this information to produce natural, context-aware responses,
which in turn helps mitigate the risk of hallucinated responses.
In this project, a holistic exploration of building a transformative question-answering system has
been followed. An extractive reader-retriever model is built and experimented with in the initial
phase. In the second phase, a generative model is built to encounter hallucinated and
context-aware answers. Finally, a RAG pipeline using the Haystack framework and Google’s
Gemini language model demonstrates the potential of RAG systems for accurate, context-aware
question answering. In each phase, the implementation is evaluated for its advantages and
drawbacks.
