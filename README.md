# Chat PDF Streamlit App

This is a Streamlit app that allows users to upload PDF and TXT files, load them into a document index, and query the index using a Chatbot powered by the OpenAI API.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/velocius-ailabs/rag-poc.git your-repository
2. Navigate to the project directory:
   ``` bash
   cd your-repository
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1. Run the Streamlit app:
   ``` bash
   streamlit run your_app.py
2. Open your web browser and go to the link provided in the terminal
3. Upload PDF and TXT files, and use the app to query the document index.

## Dependencies
1. Streamlit
2. llama_index
3. langchain
4. OpenAI API

## Configuration
Create a .env file in the project root and add your API key:
```bash
OPENAI_API_KEY=your-api-key-goes-here