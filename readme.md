# GPT_pdf_search
An LLM based python app that let you upload your own pdf documents and then ask questions related to it.

## Introduction
------------
 It is a Python app that allows you to ask question about your PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries and to frame answers in Natural Human understandable language. 
 
 Please note that the app will only respond to questions related to the loaded PDFs.


## Dependencies and Installation
----------------------------
To install this on your system please follow these steps:

1. Python 3.9 is necessary (everything is only tested on python 3.9)

2. Clone the repository to your local machine.

3. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

4. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage
-----
To run this app follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `app.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.