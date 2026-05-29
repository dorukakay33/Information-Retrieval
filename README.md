# Information Retrieval Search Engine

This repository contains a series of Information Retrieval assignments focused on building, improving, evaluating, and analysing a small search engine pipeline using a scientific-paper dataset.

The project covers the main stages of an information retrieval workflow: inspecting a document collection, building a basic retrieval system, improving search quality, evaluating results, analysing citation/link structures, and applying clustering methods to explore document groups.

## Project Overview

The goal of this project was to understand how search systems retrieve relevant documents from a collection. The notebooks follow a step-by-step workflow, starting from dataset inspection and ending with analysis and clustering.

This project is especially relevant to document-based AI systems and retrieval-augmented generation (RAG), where retrieving the right information from a document collection is an important step before generating a useful answer.

## Repository Structure

```text
Information-Retrieval/
│
├── Notebooks/
│   ├── 01_inspection.ipynb
│   ├── 02_building.ipynb
│   ├── 03_improving.ipynb
│   ├── 04_evaluating.ipynb
│   ├── 05_analysis.ipynb
│   └── 06_clustering.ipynb
│
└── README.md
```

## Notebook Descriptions

### 01 — Dataset Inspection

Initial exploration of the scientific-paper dataset. This notebook focuses on understanding the structure of the corpus, including document metadata, abstracts, summaries, and basic collection statistics.

### 02 — Building a Search Index

Construction of a basic search index for keyword-based document retrieval. This step introduces the core logic behind simple search engines, where query terms are matched to relevant documents.

### 03 — Improving Retrieval

Improvement of the retrieval system using preprocessing and ranking-related techniques. This step focuses on making the search results more relevant and useful.

### 04 — Evaluating Retrieval Results

Evaluation of the retrieval system using relevance judgments and retrieval quality measures. This step highlights the importance of measuring whether the search system returns useful results for a given information need.

### 05 — Link and Network Analysis

Analysis of citation and network structures related to the document collection. This step explores how relationships between documents can provide additional signals for understanding relevance and influence.

### 06 — Document Clustering

Application of clustering methods to group related documents and explore hidden themes in the document collection. This step connects information retrieval with broader NLP and document analysis techniques.

## Skills Demonstrated

* Information retrieval
* Search engine pipeline development
* Text preprocessing
* Indexing and keyword-based retrieval
* Ranking and retrieval improvement
* Retrieval evaluation
* Link and network analysis
* Document clustering
* Python
* Jupyter Notebook

## Relevance to Applied AI

This project demonstrates practical experience with retrieving and organizing information from large text collections. These skills are relevant to AI-powered document assistants, internal knowledge systems, search tools, and RAG-style applications where a system needs to find the right information before generating or presenting an answer.

## Tools and Technologies

* Python
* Jupyter Notebook
* pandas
* numpy
* scikit-learn
* NetworkX
* NLTK / text preprocessing tools
* matplotlib
