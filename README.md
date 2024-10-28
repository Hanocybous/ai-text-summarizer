# AI Text Summarizer

## Description
The AI Text Summarizer is a web application designed to condense lengthy texts into concise summaries using advanced natural language processing models. This project leverages the capabilities of Postman for API testing, Hugging Face for pre-trained language models, Axios for HTTP requests, and Express for building the server-side application.

## Features
- **Text Summarization**: Input any text, and the application will generate a brief summary.
- **API Integration**: Utilize Hugging Face's pre-trained models to ensure high-quality text summarization.
- **User-Friendly Interface**: Simple and intuitive interface for users to input text and receive summaries.
- **Efficient HTTP Requests**: Axios is used to handle all HTTP requests, ensuring smooth communication between the client and server.
- **Robust Backend**: Built with Express, the backend efficiently handles requests and processes data.

## Technologies Used
- **Postman**: For testing and documenting APIs.
- **Hugging Face**: To access state-of-the-art NLP models.
- **Axios**: For making HTTP requests from the client side.
- **Express**: To create a robust and scalable server-side application.

## How It Works
1. **User Input**: Users input the text they want to summarize.
2. **API Request**: The application sends the text to the Hugging Face API using Axios.
3. **Text Summarization**: The Hugging Face model processes the text and returns a summary.
4. **Display Summary**: The summarized text is displayed to the user.

## Getting Started
1. Clone the repository.
2. Navigate to inside the project folder on terminal, where I would hopefully see a package.json file
3. Do an npm install for installing all the project dependencies
4. Do an npm install -g nodemon for installing all the project dependencies
5. Then node index.js to get the app running on local host
6. The app is running on localhost:3000

## Conclusion
The AI Text Summarizer is a powerful tool for anyone needing quick and accurate text summaries. By integrating cutting-edge NLP models and efficient HTTP request handling, this project ensures a seamless user experience.
