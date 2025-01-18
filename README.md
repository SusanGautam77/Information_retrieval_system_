# Flask-Based Document Retrieval System

This project is a **Flask-based Information Retrieval System** that processes text documents and ranks them based on relevance to a user query. It uses techniques like term frequency, document frequency, and relevance score normalization.

## Features
- **Text Preprocessing:** Cleans and tokenizes text documents.
- **Relevance Scoring:** Implements a Bayesian Inference Model (BIM) with term-frequency and document-frequency calculations.
- **Interactive Web Interface:** Users can input queries and view ranked results in a user-friendly format.
- **Document Management:** Dynamically loads `.txt` documents from a specified directory.

## How It Works
1. Upload `.txt` files to the `final_data` directory.
2. Enter a query in the web interface.
3. The system processes the query and ranks documents based on their relevance.
4. View results displayed on the webpage.

## Prerequisites
- Python 3.8+
- Flask
- Basic knowledge of term-based retrieval systems.

Note: datatset are pre-defined
