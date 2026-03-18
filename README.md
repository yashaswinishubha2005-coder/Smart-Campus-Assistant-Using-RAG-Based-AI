Here is a **professional, clean README.md** (no emojis, no icons) ready to paste into GitHub:

---

# Smart Campus Assistant (RAG-Based AI Chatbot)

## Overview

Smart Campus Assistant is an AI-powered chatbot that uses Retrieval-Augmented Generation (RAG) to provide accurate and context-aware responses from institutional data sources such as PDF and CSV files. The system is designed to support students, faculty, and administrative staff by delivering reliable information while minimizing hallucinations commonly seen in traditional chatbots.

## Features

* Context-aware response generation using RAG architecture
* Support for PDF and CSV data sources
* Semantic search using vector embeddings
* Integration with large language models for response generation
* Efficient retrieval of academic resources such as sample question papers
* Web-based interface for user interaction
* Improved accuracy and reduced hallucination

## System Architecture

The system consists of the following layers:

* Frontend Layer: Handles user interaction through a web interface
* Backend Layer: Processes requests using a Flask-based server
* AI Processing Layer: Implements retrieval and generation using RAG
* Data Layer: Stores and retrieves embedded data using a vector database

## Technology Stack

* Programming Language: Python
* Framework: Flask
* Libraries and Tools:

  * LlamaIndex
  * HuggingFace Transformers
  * Sentence Transformers

## Workflow

1. The user submits a query through the interface
2. The query is processed by the backend server
3. Relevant data is retrieved from the vector database
4. The language model generates a response based on the retrieved context
5. The response is returned to the user

## Dataset

The system uses institutional data such as:

* Course information
* Faculty details
* Timetables
* Fee structure
* Student handbook documents
* Sample question papers

## Performance

The system provides improved response accuracy by grounding answers in retrieved data. It significantly reduces hallucination and ensures context relevance.

## Installation and Setup

Clone the repository:

```
git clone https://github.com/your-username/smart-campus-assistant.git
```

Navigate to the project directory:

```
cd smart-campus-assistant
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the application:

```
python app.py
```

## Use Cases

* Student support and query resolution
* Academic information retrieval
* Administrative assistance
* Smart campus automation

## Contributors

* Yashaswini B Suresh
* Team Members
