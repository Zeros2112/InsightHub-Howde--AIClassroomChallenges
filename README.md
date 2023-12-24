# InsightHub Howde @AIClassroomChallenges Hackathon
# Audio-to-Audio Chatbot 
## Overview
This project implements an audio-to-audio chatbot using FastAPI for the backend, React for the frontend, OpenAI API for natural language processing, and Eleven Labs API for text-to-speech conversion. The chatbot allows users to interact with it through audio messages, and it responds with both text and synthesized audio.

## Features
* Audio-to-Text Conversion: Utilizes the OpenAI Whisper API to transcribe incoming audio messages into text for processing.

* Text-to-Text Chatbot: Employs OpenAI's GPT-3.5-turbo model to generate responses based on user input. The chat history is stored and used for context.

* Text-to-Audio Conversion: Utilizes Eleven Labs API to convert the chatbot's textual responses into synthesized audio.

* Frontend Interface: The user interacts with the chatbot through a React-based frontend. Users can record audio messages, view the conversation history, and receive audio responses.

## Setup
### Prerequisites
* Python
* Node.js
* npm
* OpenAI API Key
* Eleven Labs API Key

### Installation
1. Clone the repository:

```
git clone <repository-url>
```
2. Backend Setup:

```
cd backend
pip install -r requirements.txt
```
Set your OpenAI and Eleven Labs API keys in the backend code.

3. Frontend Setup:

```
cd frontend
npm install
```

## Usage
1. Start the FastAPI backend:

```
cd backend
uvicorn main:app --reload
```

2. Start the React frontend:

```
cd frontend
npm start
```

3. Access the application in your browser at http://localhost:3000.

## API Reference
* `/health`: Endpoint to check the health of the backend.
* `/reset`: Endpoint to reset the conversation history.

## Known Issues
* Issue 1: Describe the first known issue and any potential workarounds.
* Issue 2: Describe the second known issue and any potential workarounds.

## Contributing
* Contributions are welcome! 

## License
This project is licensed under the MIT License.



