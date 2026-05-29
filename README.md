# Information Retrieval

This repository contains a series of Information Retrieval assignments. The project focuses on building, improving, evaluating, and analysing a basic information retrieval system using a scientific-paper dataset from PubMed.

The notebooks follow a step-by-step workflow: first inspecting the dataset, then building a simple inverted index, improving retrieval with preprocessing and ranking, evaluating search results, applying link analysis, and finally using clustering/topic modeling to explore document themes.

## Project Overview

The main goal of this project was to understand how search systems retrieve relevant documents from a collection of scientific texts. The dataset consists of article abstracts from PubMed in the Life Sciences domain.

The project covers both the technical side of information retrieval, such as indexing and ranking, and the analytical side, such as evaluating search results and exploring document relationships through networks and topics.

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
├── requirements.txt
└── README.md
```

## Notebook Descriptions

### 01 — Inspecting the Dataset

This notebook introduces the PubMed scientific-paper dataset and explores its structure. It includes basic dataset statistics such as papers per year, papers per author, authors per paper, and words in titles.

### 02 — Building a Simple Index

This notebook builds a basic inverted index using the titles and abstracts of the papers. It introduces the core logic behind keyword-based retrieval, where terms are mapped to the documents in which they appear.

### 03 — Improving the Index

This notebook improves the search index and query functions from the previous assignment. It focuses on preprocessing issues such as punctuation and singular/plural word forms, and introduces stemming and ranking methods to improve search results.

### 04 — Evaluating Search Engines

This notebook focuses on evaluating search engine results. It introduces relevance assessments and uses Cohen’s Kappa to measure agreement between human assessors on whether retrieved documents are relevant or not.

### 05 — Link Analysis

This notebook applies network-based methods to scientific papers. It works with co-authorship and citation networks and uses link analysis concepts such as PageRank to explore how network structure can support search and ranking.

### 06 — Clustering and Topic Modeling

This notebook uses clustering and topic modeling to explore groups and themes within the document collection. It prepares the document data in matrix form and applies topic modeling to identify broader topics in the scientific-paper dataset.

## Skills Demonstrated

* Information retrieval
* Dataset inspection
* Inverted index construction
* Text preprocessing
* Tokenization and stemming
* Boolean-style retrieval
* Ranking search results
* Search engine evaluation
* Relevance assessment
* Cohen’s Kappa
* Citation and co-authorship network analysis
* PageRank / link analysis
* Topic modeling
* Document exploration
* Python and Jupyter Notebook

## Tools and Libraries

* Python
* Jupyter Notebook
* NLTK
* scikit-learn
* NetworkX
* NumPy
* Matplotlib
* lda

## Relevance to Applied AI

This project is relevant to applied AI and document-based systems because many AI tools depend on retrieving the right information before producing useful output. The same general logic is important in search engines, internal knowledge systems, document assistants, and retrieval-augmented generation workflows.

