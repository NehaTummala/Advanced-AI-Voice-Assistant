# OpenAI Conversational Voice Chatbot 🤖🎙️

This project implements an AI-powered voice-enabled chatbot utilizing OpenAI's GPT models and various speech processing technologies. The chatbot features real-time conversational capabilities with both speech-to-text and text-to-speech functionalities, providing a seamless user interaction experience.

## Features 🚀

- **Conversational AI**: Leverages OpenAI's GPT-4 for dynamic and intelligent dialogue generation
- **Voice Input & Output**: Integrates OpenAI's Whisper and Azure Cognitive Services for speech-to-text and expressive text-to-speech conversions
- **Interactive UI**: Developed with Streamlit, creating an intuitive and engaging user interface
- **Persistent Session Memory**: Manages session state to provide continuity in conversations
- **Scalable Deployment**: Ready for deployment on platforms like Streamlit Sharing, AWS, and GCP

## Tech Stack 🛠️

- **Backend**: OpenAI GPT, Azure Cognitive Services
- **Speech Processing**: Whisper, Azure Text-to-Speech
- **Frontend**: Streamlit
- **Document Handling**: LangChain, ChromaDB for PDF-based Q&A
- **Environment**: Managed with Python and Dotenv

## Setup and Installation 📦

1. Clone the repository:
git clone https://github.com/NehaTummala/Advanced-AI-Voice-Assistant

  cd openai-voice-chatbot

2. Set up a Python virtual environment:
python -m venv .venv
source .venv/bin/activate # On macOS/Linux

4. Install the required dependencies:
pip install -r requirements.txt

4. Configure your OpenAI API key in a .env file:
OPENAI_API_KEY=your_api_key_here

5. Run the application:
streamlit run app.py

## Future Improvements 📌

- Add support for multiple voices and accents in TTS
- Expand document handling capabilities to include more formats
- Enhance memory capabilities using advanced vector search techniques
- Provide a comprehensive guide for cloud deployment

## Contributing 🌟

Contributions are welcome! Please fork the repository and submit a pull request with your suggested changes.

## License 📄

This project is licensed under the MIT License - see the LICENSE file for details.

Happy Chatting! 🎙️💬
