# Answer Generation and Text Search System

## Description
This project focuses on generating answers from a given text using Cohere API. It utilizes the Cohere platform for embedding texts and generating responses to specific queries.

## Installation
To set up the project, follow these steps:

1. **Set up a Virtual Environment**:
   - Create a virtual environment: `python -m venv venv`
   - Activate the virtual environment:
     - Windows: `venv\\Scripts\\activate`
     - macOS/Linux: `source venv/bin/activate`

2. **Install Requirements**:
   - Install the required packages: `pip install -r requirements.txt`

3. **Environment Variables**:
   - Create a `.env` file in the project root.
   - Add your Cohere API key and other necessary configurations to the `.env` file.

## Usage
The system allows users to input a block of text and pose questions to it. Utilizing the Cohere API, it embeds the text, searches for relevant parts, and generates answers. The main functionalities include:

- **Text Embedding**: Embeds a given text for efficient searching.
- **Article Searching**: Searches the embedded text for relevant content based on a query.
- **Answer Generation**: Generates answers to questions based on the search results.
