Flask Voice Assistant

This is a simple voice assistant web application built using Flask, which utilizes speech-to-text and text-to-speech services, along with OpenAI for generating responses to user inputs. The application supports processing both text and voice inputs.

Features

- **Speech-to-Text:** Converts spoken words into text using Watson Speech-to-Text API.
- **Text-to-Speech:** Converts text responses into spoken words using Watson Text-to-Speech API.
- **Chat with OpenAI:** Processes user input through OpenAI's GPT models to generate intelligent responses.
- **Cross-Origin Resource Sharing (CORS):** Enabled for cross-origin requests.

Requirements

- Python 3.7+
- Flask
- Flask-CORS
- Requests
- OpenAI Python SDK

Setup Instructions: Clone the Repository, then build and run

```bash
git clone https://github.com/yourusername/voice_assistant_flask.git
cd voice_assistant_flask

docker build -t voice_assistant_flask .

docker run -p 8000:8000 voice_assistant_flask
