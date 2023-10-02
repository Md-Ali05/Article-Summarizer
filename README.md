# Article Summarizer using Lamini Flan-T5 248M LLM

This project aims to provide a simple and efficient article summarizer using the Lamini Flan-T5 248M LLM downloaded from Hugging Face. The summarizer generates concise summaries of articles, approximately 150-200 words in length.

The core functionality of this project is based on the LangChain library, which facilitates the usage of the LLM for summarization.

## Components

1. **LangChain Library**: The LangChain library is crucial for interfacing with the LLM, enabling text generation and summarization.

2. **Streamlit UI**: The user interface is built using Streamlit, providing an intuitive and interactive platform for users to access the summarization functionality.

## Usage

To use the article summarizer, follow these steps:

1. **Installation**:
   - Install the required dependencies by running `pip install -r requirements.txt`.

2. **Run the Streamlit App**:
   - Execute `streamlit run app.py` to start the Streamlit application.

3. **Input**: 
   - Input the PDF article you want to summarize in the provided input box.

4. **Summarize**:
   - Click the "Summarize" button to generate a summary of the article.


## Notes

- The generated summary is approximately 100 words in length to maintain conciseness while capturing essential information from the input article.

- The Lamini Flan-T5 248M LLM, obtained from Hugging Face, forms the backbone of the summarization process.

- The LangChain library is crucial for effectively utilizing the LLM for summarization, providing a streamlined approach to interact with the model.

