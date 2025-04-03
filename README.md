# AI Voice Assistant Project

This project is a comprehensive AI-powered voice assistant designed to assist with various tasks. It can perform actions like web searches, play music, control system settings, send messages, and much more. It leverages several libraries, including speech recognition, text-to-speech, and automation libraries, to create an interactive and multi-functional assistant.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Core Libraries and Dependencies](#core-libraries-and-dependencies)
6. [Command List](#command-list)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview

This AI Voice Assistant utilizes speech recognition and text-to-speech synthesis to interact with the user. It is capable of performing a wide range of tasks, such as answering queries, controlling system operations, and automating web tasks. The assistant can also interact with external services like YouTube, WhatsApp, email, Wikipedia, and more.

The assistant's functionality includes setting alarms, creating to-do lists, taking screenshots, performing web searches, and translating text in multiple languages. The system supports various media controls, such as playing music, controlling YouTube video playback, and browsing the web.

## Features

- **Voice Interaction**: Responds to voice commands with both speech recognition and text-to-speech.
- **Web Interaction**: Perform web searches, YouTube video searches, Wikipedia lookups, and more.
- **System Control**: Shutdown, restart, sleep, and launch or close applications.
- **Media Control**: Play music from YouTube, control video playback (pause, skip, etc.).
- **Messaging**: Send WhatsApp messages, emails, and interact with contacts.
- **Time and Date**: Tell the current time, date, and set alarms.
- **To-Do Lists**: Create and manage to-do lists and save them as PDFs.
- **Multilingual Support**: Translate text between multiple languages, including Hindi and English.
- **Weather Information**: Fetch current weather information for any city.
- **News and Jokes**: Retrieve the latest news and tell jokes for entertainment.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/AI-Voice-Assistant.git
   cd AI-Voice-Assistant
   ```

2. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   If you don't have a `requirements.txt` file, you can manually install the required libraries:

   ```bash
   pip install pyttsx3 SpeechRecognition pywhatkit pytube pyjokes gTTS googletrans requests playsound pyautogui pywikihow smtplib platform pyttsx3 psutil
   ```

## Usage

1. **Run the assistant**:
   To start the voice assistant, simply run the script:

   ```bash
   python assistant.py
   ```

2. **Use voice commands**:
   The assistant will listen for commands and respond with appropriate actions. You can interact with it by saying commands like:
   - "What is the time?"
   - "Play music"
   - "Search for [query] on Google"
   - "Set an alarm"
   - "Send an email"

3. **GUI for YouTube Downloader**:
   The assistant also includes a simple GUI for downloading YouTube videos:
   - Enter the YouTube video URL.
   - Choose a destination folder.
   - Click "Download".

## Core Libraries and Dependencies

This project utilizes several key Python libraries and modules to function effectively:

- **Speech Recognition**: Used for recognizing spoken commands.
- **pyttsx3 & gTTS**: Libraries for text-to-speech synthesis.
- **pywhatkit**: For automating tasks like playing YouTube videos and controlling web browsers.
- **pytube**: Used to download YouTube videos.
- **pyjokes**: For telling jokes.
- **googletrans**: For translating text between languages.
- **requests & BeautifulSoup**: For fetching and parsing web data (e.g., weather, news).
- **pyautogui**: For automating GUI tasks like taking screenshots and controlling system settings.
- **wikipedia & pywikihow**: For searching Wikipedia and how-to guides.
- **smtplib**: For sending emails.

## Command List

Here is a list of commands the assistant can respond to:

### General Commands
- "Hello" or "Hey" - The assistant greets the user.
- "Bye" or "Exit" - The assistant says goodbye and exits.

### System Control
- "Shut down" - Shuts down the computer.
- "Restart" - Restarts the computer.
- "Sleep" or "Nap" - Puts the assistant into idle mode.

### Time and Date
- "What time is it?" or "Tell me the time" - Tells the current time.
- "What is the date today?" - Tells the current date.
- "Set an alarm for [time]" - Sets an alarm.

### Entertainment
- "Play music" or "Play song" - Plays a song or music from YouTube.
- "Tell me a joke" - Tells a random joke.
- "Search on YouTube for [query]" - Performs a YouTube search.
- "Search on Google for [query]" - Performs a Google search.

### Web Automation
- "Open [website name]" - Opens the specified website.
- "Search Wikipedia for [query]" - Searches Wikipedia.
- "Tell me about [query]" - Gets a Wikipedia summary.

### Messaging
- "Send a WhatsApp message to [contact]" - Sends a WhatsApp message.
- "Send an email to [email]" - Sends an email.
  
### Miscellaneous
- "Take a screenshot" - Takes a screenshot and saves it.
- "Translate [text] from Hindi to English" - Translates text from Hindi to English.
- "What is the weather in [city]" - Fetches weather information for the specified city.
- "Create a to-do list" - Lets the user add tasks to a to-do list and generate a PDF.

## Contributing

Contributions to the project are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add feature'`).
4. Push to your branch (`git push origin feature-name`).
5. Create a new pull request.

## License

This project is licensed under the MIT License.

---

This README includes an overview of the project, installation steps, command list, and other important details for users and developers alike. It will help users understand the functionality of the AI assistant and guide them through setup and usage. Feel free to modify or extend the information as needed!
