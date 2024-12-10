# rag-chatbot
RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot designed to provide intelligent, context-aware responses by leveraging a blend of retrieval and generative AI techniques. This project includes functionalities for integrating domain-specific documents and deploying a chatbot capable of providing precise answers based on the provided PDFs.

Features

Retrieval-Augmented Generation: Combines document retrieval and generative AI to provide accurate and context-specific answers.

Custom Knowledge Base: Integrates PDF documents (01.pdf, 02.pdf, 03.pdf) to create a personalized information repository.

Interactive Jupyter Notebook: Includes a notebook (rag_notebook.ipynb) for development, exploration, and demonstration.

Deployable Script: Contains app.py for easy deployment of the chatbot application.


Project Structure

app.py: Main application script to run the chatbot.

rag_notebook.ipynb: Jupyter Notebook for testing and development.

pdfs/: Folder containing domain-specific documents for the chatbot's knowledge base.


Getting Started

1. Clone the repository.


2. Install the necessary dependencies (listed in requirements.txt if available).


3. Run app.py to start the chatbot.


4. Use the rag_notebook.ipynb to explore the chatbot's retrieval

   import zipfile
import os

# Define the path to the uploaded file and extraction directory
uploaded_file_path = "/mnt/data/rag chatbot .zip"
extraction_dir = "/mnt/data/rag_chatbot_extracted/"

# Extract the contents of the zip file
with zipfile.ZipFile(uploaded_file_path, 'r') as zip_ref:
    zip_ref.extractall(extraction_dir)

# List the extracted contents
extracted_files = []
for root, dirs, files in os.walk(extraction_dir):
    for file in files:
        extracted_files.append(os.path.join(root, file))

extracted_files

❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹❤‍🩹


The uploaded file;
1. app.py - Likely the main application script for the chatbot.


2. rag_notebook.ipynb - A Jupyter Notebook, possibly for development, testing, or demonstrating functionality.


3. PDFs (01.pdf, 02.pdf, 03.pdf) - Documents that might be relevant to the chatbot's context or knowledge base.
