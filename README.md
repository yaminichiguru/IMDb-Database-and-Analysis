# IMDb-Database-and-Analysis

# Project Overview
This project focuses on analyzing a large dataset from the DBLP computer science bibliography, which manages information about authors, their publications, conferences, and citations in the field of computer science. The goal is to extract useful insights from the dataset by representing the data as graphs and applying graph theory concepts for analysis.

# Dataset
The dataset is in JSON format and consists of the following files:

4 JSON files containing information on papers, authors, conferences, and citations (~1GB each).
Metadata file (metadata-info-for-v10.doc) to interpret the data.

# Objective
The project aims to analyze the DBLP dataset using graph characteristics. The analysis is divided into multiple tasks such as:

Constructing a Known Authors Graph – Connecting co-authors of each paper.
Constructing a Citation Graph – Representing papers and their citation relationships.
Constructing a Conference-Author Graph – Connecting authors with conferences where they have published papers.

# Key Analyses Performed
Analysis 0: Running network characteristics on the created graphs to understand their properties.

Analysis 1: Testing the approach with a sample dataset and comparing it with ground-truth data.

Analysis 2: Finding maximal groups of authors who are mutually connected.

Analysis 3a: Finding the most cited papers.

Analysis 3b: Identifying authors who have published the most papers.

# Graph Construction and Pre-processing
Pre-processed the dataset to extract relevant data for graph creation.

Constructed the following graph structures:

Known Authors Graph: Undirected graph connecting co-authors.

Citation Graph: Directed graph representing citation relationships between papers.

Conference-Author Graph: Undirected graph connecting authors to conferences.

# Tools and Libraries Used
Python: Core programming language used for data processing and analysis.

NetworkX: Library used to create and analyze graph data structures.

Matplotlib: Used for visualizing graphs and results.

Pandas: Used for handling and processing the dataset.

Google Colab/Jupyter Notebook: Environment for running and testing code.

# Results
Identified top authors, conferences, and cited papers from the dataset.

Created and analyzed various graph structures to infer collaboration patterns and citation networks.

# Acknowledgments
This project was part of the Foundations of Computing course (DASC 5300/CSE 5300) taught by Prof. Sharma Chakravarthy in Fall 2022.
