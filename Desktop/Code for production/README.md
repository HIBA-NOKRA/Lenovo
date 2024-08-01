# API-llamaindex

This repository contains the code for the application of Retrieval Augmented Generation (RAG) using LlamaIndex. The API is built using FastAPI, providing a robust and scalable solution for generating precise and contextually accurate responses by leveraging extensive.

## Installation

You'll need to:

1- Clone the repository:

```bash
git clone https://github.com/hostifai/api-kb.git
```

2- Install the necessary dependencies:

```bash
pip install Flask
pip install llama-index
pip install openai
```

## Configuration

Add your OpenAI API key as an environment variable:

```bash
os.environ["OPENAI_API_KEY"] = "your_openai_api_key"
```

## Testing the API

Open your browser to send a GET request to the API.

```bash
http://localhost:5601/query?text=<your_text>&hotelId=<your_hotel_id>
```

Replace <your_text> with the question or query you want to ask and <your_hotel_id> with the relevant hotel ID.
