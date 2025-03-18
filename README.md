# Ask a Question About an Image - Web App

## Overview
This project is a Streamlit-based web application that allows users to upload an image and ask questions about it. The app utilizes LangChain and OpenAI's GPT model to analyze the image and generate relevant responses. It supports features like image captioning and object detection.

## Features
- Upload an image in JPEG or PNG format.
- Ask questions related to the uploaded image.
- Receive AI-generated responses based on image analysis.
- Uses LangChain with conversational memory for better context retention.

## Requirements
Ensure you have Python installed along with the following dependencies:

```bash
pip install streamlit langchain openai
```

## Usage
### Running the Web App
To start the Streamlit web app, run:

```bash
streamlit run app.py
```

### Uploading an Image and Asking Questions
1. Open the Streamlit web interface.
2. Upload an image (JPEG, JPG, or PNG format).
3. Enter a question related to the image.
4. The AI processes the image and returns an answer.

## How It Works
1. The user uploads an image through the Streamlit interface.
2. The image is temporarily saved using `NamedTemporaryFile`.
3. The LangChain agent is initialized with tools for image captioning and object detection.
4. The user enters a question, and the agent processes it along with the image.
5. The response is displayed on the interface.

## Technologies Used
- **Streamlit** - For the web UI.
- **LangChain** - For managing AI-powered interactions.
- **OpenAI GPT-3.5** - As the language model.
- **Image Processing Tools** - For extracting information from the image.

      
