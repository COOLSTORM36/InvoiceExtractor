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

`pip install markitdown langchain-community langchain langchain_openai openai`

## Usage

1. **Set Up API Key**: Ensure your OpenAI API key is set as an environment variable `OPENAI_API_KEY` or pass it directly in the code.

2. **Convert Invoice File to Text**:
   - Use the `md_convert(file_path)` function to convert your invoice file into text format.

3. **Parse Invoice Information**:
   - Use the `parse_invoice(text)` function to extract structured information from the invoice text.


## Notes

- Ensure that your OpenAI API key is correctly set up in your environment.
- Modify `filepath` to point to your actual invoice file location.
- This project uses GPT-4o; ensure you have access to this model via OpenAI.

## License

This project is licensed under the MIT License.
