Port of Portland Bid Tab Project 
Oregon State University MBA Capstone — BANA577

Project Overview
End-to-end analytics system built on unstructured bid tabulation
data from the Port of Portland (2021-2024). Transforms manually searched PDF
bid tabs into a structured, searchable intelligence system that supports
lowest-cost contractor identification and procurement decision making.

Business Problem:
The Port of Portland manages hundreds of infrastructure bids annually across
roadwork, electrical, drainage, airfield, and marine project types. Bid
tab data existed only in inconsistently formatted PDF files — making
contractor comparison, price benchmarking, and trend analysis time-consuming
and error prone.
This system solves that by building a full analytical pipeline from raw data
extraction through NLP clustering, project classification, and an AI-powered
natural language chatbot.



Key Analytical Findings

Kodiak Pacific Construction Co submitted the most bids (7) across the dataset
Cluster 0 (Site Utilities) was the most diverse material category requiring hierarchical subclustering into 14 subgroups
Airfield Pavement and Pavement Removal emerged as the most common project types
Bid activity showed seasonal patterns with peaks in spring and summer months


Technologies
Python, pandas, scikit-learn, NLTK, rapidfuzz, LangChain, OpenAI API,
FAISS, matplotlib, seaborn, K-means clustering, TF-IDF vectorization,
Retrieval-Augmented Generation (RAG)

Setup
pip install pandas scikit-learn nltk rapidfuzz langchain langchain-openai langchain-community faiss-cpu openai matplotlib seaborn openpyxl
Set OpenAI API key before running the chatbot:
export OPENAI_API_KEY=your_key_here

Raw bid tabulation data files are not included in this repository.
Input data consists of Port of Portland procurement records (2021-2024).
