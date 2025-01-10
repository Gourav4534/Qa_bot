# QA Bot Project
![QA Bot Screenshot]( https://github.com/Gourav4534/Qa_bot/blob/main/Qa_bot_screenshot.png?raw=true)          
This project implements a Question-Answering (QA) bot that can answer queries based on a PDF document provided by the user. It uses IBM WatsonX for language model inference, LangChain for text processing, and Gradio for building the user interface. The bot can be used for answering questions by searching through the uploaded PDF document.

## Features
- **PDF Upload**: Upload a PDF file containing relevant information.
- **Question Input**: Ask questions related to the content of the uploaded PDF.
- **Answer Retrieval**: The bot answers the questions based on the document, using a retrieval-augmented generation (RAG) model.
- **Gradio Interface**: User-friendly web interface for interacting with the bot.

## Requirements

Ensure you have the following dependencies installed:

- `gradio` - for creating the interactive web interface.
- `ibm-watsonx-ai` - for using IBM's WatsonX models and embeddings.
- `langchain_ibm` - for LangChain integration with IBM WatsonX.
- `langchain` - for document splitting and processing.
- `langchain_community` - for vector store and PDF document loaders.

You can install the necessary libraries using the following command:

```bash
pip install gradio ibm-watsonx-ai langchain_ibm langchain langchain_community
