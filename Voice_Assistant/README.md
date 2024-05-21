# Siri Personal Assistant

This project is a simple personal assistant named "Siri" that can perform various tasks using voice commands. It utilizes the `speech_recognition`, `pyttsx3`, `pywhatkit`, `datetime`, and `wikipedia` libraries to listen to your voice, process commands, and provide responses.

## Features

- **Play Music:** Plays a song from YouTube when you say "play" followed by the song's name.
- **Tell Time:** Tells the current time when you ask "what is the time" or "tell me the time".
- **Tell Date:** Tells the current date when you ask "what is the date" or "tell me the date".
- **Greetings:** Responds to "how are you" and "who are you".
- **Wikipedia Search:** Provides a brief summary of a person or object when you say "who is" or "what is" followed by the name.
- **Exit:** Stops the assistant when you say "exit".

## Usage

1. Run the script:
    ```bash
    python siri.py
    ```
2. Speak your commands clearly into the microphone. Example commands include:
    - "play Despacito"
    - "what is the time"
    - "what is the date"
    - "how are you"
    - "who is Albert Einstein"
    - "exit"

## Requirements

- Python 3.x
- SpeechRecognition
- pyttsx3
- pywhatkit
- datetime
- wikipedia
