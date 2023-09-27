#Talk2PDF Chat Application

#Introduction
The Talk2PDF Chat Application is a specialized tool built with Python that offers a unique interaction with your PDF documents. Using this app, you can naturally inquire about details or information found within the uploaded PDFs. Backed by a sophisticated language model, the application sifts through the content and supplies precise answers. However, keep in mind that it is designed to address queries specifically about the content within the uploaded documents.

#How It Works
To achieve its functionality, the application employs a sequence of operations:

PDF Loading: Multiple PDF documents are read, and the text contained within is extracted.

Text Chunking: This raw text is then segmented into manageable chunks, priming it for efficient processing.

Language Model Interaction: Vector representations (embeddings) of these chunks are generated using a language model.

Similarity Assessment: When you pose a question, the app evaluates it against these chunks, pinpointing the segments with the closest semantic resemblance.

Crafting a Response: These relevant segments are relayed back to the language model, which then curates a response based on the content of the documents.
Dependencies and Installation

#Installing 
To get the Aberdeen Advisors MultiPDF Chat Application up and running, follow these steps:

Clone the repository onto your computer.
With the help of the following command, install the necessary dependencies:

pip install -r requirements.txt

Secure an API key from OpenAI, and subsequently insert it into the .env file located within the main project directory.
Confirm that you've taken care of the dependencies and integrated the OpenAI API key into the app.py script.

#Usage
Operating the MultiPDF Chat Application is straightforward:
Using the Streamlit CLI, initiate the app.py script:

streamlit run app.py

The UI of the application will spring to life in your default web browser.

Follow the on-screen directives to load your choice of PDF documents.

Commence your natural language conversations with the app regarding the content of the loaded PDFs.

