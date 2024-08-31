# 🦜️🔗 LangChain Research v0.2.15 

## Overview

This repository contains research and experimentation related to the [LangChain](https://python.langchain.com/v0.2/docs/introduction/) library, a comprehensive toolkit for developing applications involving natural language processing (NLP) and large language models (LLMs). The primary objective of this project is to explore various components of LangChain, understand their functionalities, and leverage them to create an efficient pipeline for a Retrieval-Augmented Generation (RAG) system.

## Contents

- **Investigation of LangChain Components**: A detailed examination of various modules and components of the LangChain library, including:

  - **Prompt Templates**: Crafting templates for generating prompts and managing interactions with language models.

  - **Output Parsers**: Parsing the output from LLMs into structured formats, such as Python dictionaries.

  - **Document**: Abstract representation of text segments.

  - **Text Splitters**: Methods to divide text into manageable chunks for processing, with a focus on `RecursiveCharacterTextSplitter` and `SemanticChunker`.

  - **Vector Stores**: Implementing and using vector databases for efficient information retrieval, tested with `Chroma` and `Qdrant`.

  - **Retrieval Models**: Exploring different retrieval models, including BM25, to perform *Hybrid Search* on Qdrant.

  - **LangChain Expression Language (LCEL)**: Utilizing the `Runnable` interface to test different chains for various use cases.

  - **LangSmith**: Tools for tracking the performance of chains.

- **Development of a RAG Pipeline**: Utilizing insights from the research to develop a Retrieval-Augmented Generation pipeline. This pipeline integrates:
  - Collecting text from the web.
  - Splitting text in two steps to improve context comprehension.
  - A robust retrieval mechanism to fetch relevant documents from a vector store.
  - A language model that uses the retrieved information to generate accurate and contextually relevant responses.

The details of these components and implementations are available in the accompanying notebooks.

## Sources

- [LangChain for LLM Application Development course of **learn.deeplearning.ai** ](https://learn.deeplearning.ai/courses/langchain/lesson/1/introduction)
- [LangChain Documentation](https://python.langchain.com/v0.2/docs/introduction/#tutorials)
- [LangSmith](https://www.langchain.com/langsmith)
- [Qdrant Frameworks Documentation](https://qdrant.tech/documentation/frameworks/langchain/)
- [LangChain RAG Tutorials](https://python.langchain.com/v0.2/docs/tutorials/rag/)
