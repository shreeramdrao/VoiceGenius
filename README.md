# Voice Genius

Voice Genius is a simple web application that utilizes the OpenAI API and the SpeechRecognition API to create a voice-accessible chat interface powered by the GPT-3.5 turbo model. With Voice Genius, users can interact with an AI-powered chatbot using their voice input.

## Features

- **Voice-Enabled Chat Interface**: Users can start a conversation with the chatbot by clicking the "Start" button and speaking into their device's microphone.

- **Real-time Chat Responses**: As users speak, their input is transcribed and sent to the OpenAI API for processing. The chatbot's responses are displayed in real-time within the web interface.

- **Bootstrap Styling**: The web interface is styled using Bootstrap, providing a clean and responsive design.

## Prerequisites

- Node.js installed on your machine.
- OpenAI API key.

## Getting Started

```bash
git clone https://github.com/yourusername/voice-genius.git
cd voice-genius
npm install
```

Replace `"YOUR_OPENAI_API_KEY"` in `app.js` with your actual OpenAI API key.

```bash
node app.js
```

Open your web browser and go to `http://localhost:3000` to access the Voice Genius web application.

## Usage

1. Click the "Start" button to enable voice input.
2. Speak into your device's microphone to ask a question or start a conversation with the chatbot.
3. The chatbot's responses will be displayed in real-time within the web interface.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, feature requests, or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
