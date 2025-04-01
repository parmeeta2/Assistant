# MAX - Personal Desktop Assistant

# Overview

MAX is a personal desktop assistant that can perform various tasks such as voice recognition, opening websites, fetching weather updates, playing songs, capturing screenshots, and more. The assistant interacts through speech and can process voice commands to execute different functions.

# Features

1. Voice Recognition: Takes user commands through speech.

2. Time & Date: Provides the current time and date.

3. CPU Status: Displays CPU usage, battery level, RAM usage, and storage status.

4. Jokes: Tells a random joke.

5. Screenshot: Captures and saves a screenshot.

6. Camera: Opens the webcam and allows the user to capture images.

7. Wikipedia Search: Fetches a brief summary from Wikipedia.

8. Web Browsing: Opens user-specified websites.

9. Google Search: Performs a Google search for a given query.

10. Music Playback: Plays a song from a designated folder.

11. Memory Storage: Remembers user notes and recalls them on command.

12. Weather Updates: Provides the weather forecast for a specified city.

13. Help Function: Lists all available commands for the assistant.

# Installation

# Prerequisites

 1. Ensure you have Python installed along with the required dependencies. Install them using:

 2. pip install pyttsx3 speechrecognition wikipedia smtplib webbrowser requests os pyautogui psutil pyjokes opencv-python

# Usage

1. Run the script: python assistant.py

2. Speak your commands clearly into the microphone.

3. Use the following commands:

🟢 "My introduction" - Hear MAX's introduction.

🕒 "Time" - Get the current time.

📆 "Date" - Get the current date.

🖥️ "CPU Status" - Check system performance.

😂 "Joke" - Hear a joke.

📸 "Screenshot" - Take a screenshot.

🎥 "Camera" - Capture an image.

📖 "Wikipedia [query]" - Search Wikipedia.

🌐 "Open website" - Open a website.

🔍 "Search" - Perform a Google search.

🎵 "Song" - Play a song.

📝 "Remember" - Store a note.

🔎 "Know" - Recall stored notes.

☁️ "Weather" - Get weather details.

🆘 "Help" - List all commands.

⏻ "Offline" - Exit the assistant.

# Configuration

1. Update FolderPath to specify the location for storing screenshots.

2. Update CameraPath to save captured images from the webcam.

3. Update MusicPath to the folder containing your music.

4. Update ChromePath with the correct path of your Chrome browser.

5. Update YourAPIkey with your OpenWeatherMap API key for weather updates.

# Dependencies

✅ Python 3.x

✅ pyttsx3

✅ speechrecognition

✅ wikipedia

✅ smtplib

✅ webbrowser

✅ requests

✅ os

✅ pyautogui

✅ psutil

✅ pyjokes

✅ opencv-python
