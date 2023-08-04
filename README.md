## VoiceGPT using ChatGPT

This repository contains a Python script that utilizes OpenAI's GPT-3 API for VoiceGPT. The script allows you to interact with the GPT-3 model by speaking questions or prompts and receiving text-based responses.

## Features

- Transcribe audio files into text using the SpeechRecognition library
- Generate responses using OpenAI's GPT-3 API
- Convert generated text responses into speech using the pyttsx3 library

## Setup

To run the script, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python libraries:
   ```
   pip install openai pyttsx3 SpeechRecognition
   ```
3. Set up your OpenAI API key. Visit [OpenAI Platform](https://platform.openai.com) and create a new API key.
4. Replace `YOUR OPENAI KEY` in the code with your actual OpenAI API key.
5. Run the script:
   ```
   python main.py
   ```

## Usage

1. Say "Genius" to start recording your question.
2. Speak your question after the prompt.
3. The audio will be transcribed into text.
4. GPT-3 will generate a response based on the input prompt.
5. The response will be read aloud using text-to-speech.

## Requirements

- Python 3.7 or above
- OpenAI API key
- Microphone

Please note that this script relies on an active internet connection and access to OpenAI's GPT-3 API.

## Disclaimer

This project is an example implementation and may require modifications to fit your specific use case. Refer to the OpenAI documentation for any concerns regarding API usage and billing.

Feel free to customize and enhance this script as per your requirements.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This script was created using OpenAI's GPT-3 API and various Python libraries, including pyttsx3 and SpeechRecognition.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## Contact

For any questions or feedback, feel free to contact the project maintainer: [Ansh srivastava](mailto:ansh.srivastava0987@gmail.com)
