# Invoice Extractor

This project is designed to extract specific information from invoice documents using OpenAI's GPT-4 model via LangChain. The extracted information includes the invoice number, date, total amount, and vendor name.

## Features

- **Invoice Text Extraction**: Converts invoice files into text using `MarkItDown`.
- **Information Parsing**: Uses LangChain to parse invoice text and extract structured information.
- **OpenAI Integration**: Leverages OpenAI's GPT-4 model for natural language understanding.

## Prerequisites

- Python 3.x
- Google Colab or a local Python environment

## Installation

To install the necessary packages, run:

```pip install markitdown langchain-community langchain langchain_openai openai```
