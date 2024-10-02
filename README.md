
# Chatbot Application

This project is a chatbot web application that leverages **Microsoft DialoGPT**, a pre-trained language model designed to generate human-like responses to given prompts. The chatbot is integrated with **Flask**, a popular Python web framework, to handle user interactions via a chat interface.

## Project Structure

- **app.py**: The main application file that runs the Flask server and integrates with DialoGPT to generate responses.
- **requirements.txt**: This file lists the dependencies required to run the application.
- **static**: This folder contains static files such as stylesheets and images.
  - **style.css**: CSS file that styles the front-end interface.
  
- **templates**: This folder contains HTML templates for rendering the web pages.
  - **index.html**: The main HTML file for the chatbot's interface.

## Features

- **Microsoft DialoGPT Integration**: The chatbot generates human-like responses to user input using DialoGPT.
- **Flask Backend**: Flask is used to handle server-side logic and HTTP requests.
- **Interactive Front-End**: The front-end is built with HTML, CSS, and JavaScript for a dynamic user experience.
- **jQuery for HTTP Requests**: jQuery is used to manage asynchronous HTTP requests between the front-end and back-end.

## Screenshot

    

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd chatbot-main
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open a browser and go to `http://127.0.0.1:5000/` to interact with the chatbot.

## Dependencies

Ensure that you have the following dependencies installed:

- Flask
- Transformers (for Microsoft DialoGPT)
- jQuery (for front-end HTTP requests)
- Any other dependencies listed in `requirements.txt`

## Usage

Once the server is running, we can interact with the chatbot through the web interface. Type a message, and the chatbot will generate a response using Microsoft DialoGPT based on your input.

