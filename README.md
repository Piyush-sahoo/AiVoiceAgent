# Temperature Control Voice Assistant

This project is a **voice assistant** designed for controlling temperatures in different zones of a building. It uses LiveKit's agent framework and integrates OpenAI and Silero plugins for natural language processing and speech-to-text capabilities.

## Features

- **Voice Interaction**: Communicates with users via voice for a seamless experience
- **Temperature Management**: Get and set temperatures for specific zones (Living Room, Bedroom, Kitchen, Bathroom, Office)
- **Short and Concise Responses**: Optimized for clarity in voice interactions

## Project Structure

- **`api.py`**: Implements the AssistantFnc class, providing functionality to get and set temperatures for various zones
- **`main.py`**: Entrypoint for the voice assistant application. Sets up the assistant's voice capabilities and defines its behavior
- **`requirements.txt`**: Lists the Python dependencies required for the project

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   Ensure you have Python 3.8+ installed. Then, install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**:
   Create a `.env` file to configure any necessary environment variables (e.g., API keys for OpenAI plugins).

## Usage

1. **Run the application**:
   Execute the main file to start the voice assistant:
   ```bash
   python main.py
   ```

2. **Interact with the assistant**:
   * Ask for the temperature in a specific room:
     ```
     "What is the temperature in the living room?"
     ```
   * Set the temperature in a specific room:
     ```
     "Set the temperature in the bedroom to 22°C."
     ```

## Dependencies

The project relies on the following libraries:

* `livekit-agents>=0.8.7`: Core agent framework
* `livekit-plugins-openai>=0.8.1`: OpenAI integration for LLM, STT, and TTS capabilities
* `livekit-plugins-silero>=0.6.4`: Silero plugin for Voice Activity Detection (VAD)
* `python-dotenv~=1.0`: For managing environment variables

## Future Enhancements

* Expand support for additional zones
* Improve natural language understanding
* Add more voice-controlled functionalities

## Contributing

Contributions are welcome! Feel free to fork this repository and create pull requests.

## License

This project is licensed under the MIT License.
