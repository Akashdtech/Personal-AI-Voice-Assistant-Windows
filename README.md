# Personal-AI-Voice-Assistant-Windows
Raven is a simple voice-controlled assistant that responds to voice commands to perform various tasks, such as opening applications, browsing the web, fetching Wikipedia summaries, and announcing the current time.

Features:

    Voice Activation: Listens for the wake word "Raven" to start processing commands.
    Application Control: Opens Microsoft Excel and Notepad via voice command.
    Web Browsing: Opens Google and YouTube using Mozilla Firefox.
    Wikipedia Search: Retrieves and reads summaries of topics from Wikipedia.
    Time Announcement: Announces the current time upon request.
    Speech Output: Uses text-to-speech (TTS) to respond to the user.

Installation:

    Ensure you have the required dependencies installed before running the script.

        pip install SpeechRecognition pyttsx3 wikipedia PyAudio
        sudo apt install espeak portaudio19-dev python-all-dev python3-all-dev

Usage:

    Run the script.
    Say "Raven" to activate the assistant.
    Give a command, such as:
        "Open Google"
        "Search Wikipedia for artificial intelligence"
        "What time is it?"
    Say "Exit" to close the assistant.

Notes:

    Ensure that your microphone is enabled and working properly.
    The script currently supports Windows paths for application execution. Modify paths accordingly for other operating systems.
