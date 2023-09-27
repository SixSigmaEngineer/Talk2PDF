# Talk2PDF Chat Application 💬🦜🔗

## Introduction
The Talk2PDF Chat Application is a specialized tool that allows users to interact seamlessly with their PDF documents. Built with Python, this tool enables users to pose questions about content within the uploaded PDFs, and in return, it fetches precise answers using the OpenAI API.

**Note**: This application specifically addresses queries related to the content of the uploaded documents.

## How It Works
The application delivers its unique functionality through a series of steps:

1. **PDF Loading**: Allows users to upload multiple PDF documents, from which the textual content is extracted.
   
2. **Text Chunking**: The extracted text is then broken down into manageable chunks, making it apt for efficient querying.
   
3. **Language Model Interaction**: Each of these chunks is transformed into vector representations (embeddings) using a language model.
   
4. **Similarity Assessment**: Upon receiving a user's question, the application compares it with these embeddings, identifying the chunks that are semantically closest to the query.
   
5. **Crafting a Response**: The identified relevant chunks are processed by the language model, which crafts a coherent response based on the content.

## Dependencies and Installation

### Installing
Set up the Talk2PDF Chat Application with these steps:

*Note - Ensure you Have Python and Git Installed on your Machine! 
1. Clone the repository to your local machine (git clone).
2. Install all the required dependencies using:
   ```bash
   pip install -r requirements.txt
3. Obtain an API key from OpenAI. Then, populate the app.py file in the main project directory with this key.
4. Use the batch file to run the program!

## EXAMPLE

![Demo](/docs/Screenshot 1.png)

## Contributing
This repository is designed for instructional use and is not open to additional contributions. It acts as supplementary content for a YouTube tutorial showcasing how to construct this project. You're welcome to adapt and improve the app to suit your needs.

## License
The Talk2PDF App is released under the [MIT License](https://opensource.org/licenses/MIT).
