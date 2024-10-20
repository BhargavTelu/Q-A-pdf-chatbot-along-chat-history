
# Chatbot for Documents

This repository contains the code for a document-based chatbot platform. The chatbot enables users to query various file formats (PDF, Excel, JSON, Text) and retrieve specific information without manually searching through long documents. The system leverages modern NLP models, sentence embeddings, and vector storage to provide accurate and efficient document querying.
## Features

- Multi-format Document Support: Upload files in PDF, Excel, JSON, and Text formats.
- Natural Language Queries: Query documents in plain language to find specific information.
- Efficient Search: Avoid manually scanning long documents by using a chatbot for intelligent querying.
- NLP-Powered: Utilizes advanced NLP techniques such as sentence embedding for better information retrieval.
- User-friendly Interface: Built using Streamlit for easy user interaction.
- Storage Optimization: Uses Pinecone for vector storage to handle large amounts of document data.


## Technologies Used

- LangChain: For text extraction from documents.
- Hugging Face Transformers: For sentence embedding.
- Pinecone: To store and manage document vectors for fast querying.
- Streamlit: Provides a simple, interactive web-based interface for users to interact with the chatbot.
- OpenAI API: For generating chatbot responses and processing user queries.
## Installation

Clone the repository:

```bash
  git clone https://github.com/yourusername/chatbot-for-documents.git

```

Navigate to the project directory:

```bash
  cd chatbot-for-documents

```
Create and activate a virtual environment 

```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows

```

Install the required dependencies:

```bash
pip install -r requirements.txt

```


## Usage

1. Run the application:


```bash
streamlit run app.py

```

2. Upload a Document: Open the application in your browser and upload a document (PDF, Excel, JSON, or Text).

3. Ask a Question: Input your natural language question in the chatbot interface (e.g., "What is the total revenue for Q1 2023?").

3. Get the Response: The chatbot will return the relevant section or data from the document.

## Project Structure

```bash
chatbot-for-documents/
│
├── app.py                    # Main Streamlit app file
├── requirements.txt           # Required Python packages
├── README.md                  # Project documentation (this file)
└── ...

```


## Future Enhancements
- Support for additional file formats: Extend support to other formats such as Word documents.
- Multi-lingual support: Enable querying in languages other than English.
- Improved Accuracy: Continue improving the sentence embedding model for more accurate search results.

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome!

## Contact
For any questions or inquiries, reach out to:

Bhargav Telu - LinkedIn
