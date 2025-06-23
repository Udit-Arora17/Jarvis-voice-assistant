# Jarvis – Your Personal Voice Assistant (Python)

Jarvis is a voice assistant built using Python.  
It listens to your voice commands and performs tasks like opening websites, telling jokes, copying text, and more.  
It's a beginner-friendly project designed to help you explore speech recognition, automation, and simple AI features.

---

## 📑 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Example Commands](#example-commands)
- [Notes](#notes)
- [Made By](#made-by)
- [Future Ideas](#future-ideas)

---

## Features

- Voice recognition using your mic  
- Speaks responses using text-to-speech  
- Opens websites like YouTube, Google, etc.  
- Tells random programming jokes  
- Automates copy-paste tasks  
- Uses OpenAI (optional) to give smart replies  
- Can play your custom music from a playlist  
- Expandable with features like weather, GUI, and more

📝 For music, create a new file named `musicPlaylist.py` and add your songs in a dictionary as:

```python
# musicPlaylist.py 
songs = {
        "song_name":"url",
        "another_song_name":"url"
    }
```

## Technologies Used
-This project uses several Python libraries (all listed in requirements.txt), including:

-pyttsx3 – Text-to-speech

-speech_recognition – Voice input

-pyautogui, pyperclip – Automation and clipboard tasks

-webbrowser – To open websites

-pyjokes – For jokes

-openai – (Optional) for chatbot replies

-requests, time, etc.

---

## How to Run
Clone this repo
git clone https://github.com/yourusername/jarvis-voice-assistant.git

Go to the project folder
cd jarvis-voice-assistant

Install the required libraries
pip install -r requirements.txt #it should be in your folder in which you are working with the code

(Optional) Add your music
Create a musicPlaylist.py file as shown above.

Run the script
python jarvis.py

---

## Example Commands
“Open YouTube”

“Tell me a joke”

“Open Instagram”

“Search on Google”

“Play believer” (if added to your playlist)

“Use OpenAI to reply” (if API key added)

---

## Notes
Make sure your microphone is working and not muted.

If you're using the OpenAI feature, add your API key in the code where needed.

Some functions like mouse click or app open are customized for personal setup (can be changed).

You can expand this project by adding more voice commands, APIs, or a GUI.

---

## Made By
Udit Arora – 8th-grade coder learning Python and building cool things.
Follow my journey: [github.com/Udit-Arora17]

---

## Future Ideas
Add weather updates using API

Play songs using voice

Show system info or battery status

Add a graphical interface using Tkinter or PyQt

Run desktop apps through voice

---