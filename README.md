# InfoTune
InfoTune is a voice-activated assistant developed in Python. It leverages speech recognition and text-to-speech to interact with users and can perform various tasks, such as playing YouTube videos, fetching information from Wikipedia, and providing the current date and time.

## Table of Contents
- [Overview](#overview)
- [Setup](#setup)
- [Features](#features)
  1. [Text-to-Speech](#text-to-speech)
  2. [Speech Recognition](#speechrecognition)
  3. [Current Date and Time](#currentdateandtime)
  4. [Wikipedia Search](#wikipediasearch)
  5. [YouTube Playback](#youtubeplayback)
- [Usage](#usage)

## Overview
InfoTune is designed to provide a hands-free, interactive experience where users can make voice commands to retrieve information, play media, or receive responses. It utilizes several Python libraries:

SpeechRecognition: For capturing voice commands

Pyttsx3: For converting text responses to speech

PyWhatKit: For playing videos on YouTube

Wikipedia: For retrieving brief information summaries

Datetime: For providing current date and time information
## Setup
 1. Clone the Repository:
    ```bash
    git clone https://github.com/your-username/InfoTune.git
    cd InfoTune
 2. Install Required Libraries: Ensure you have the following packages installed. You can install them using pip.
    ```bash
     pip install SpeechRecognition pyttsx3 pywhatkit wikipedia
 3.  Set Up Speech Recognition: You may need to install additional audio drivers for SpeechRecognition. Refer to the SpeechRecognition documentation if you encounter any issues.

## Features

- Text-to-Speech

   InfoTune uses pyttsx3 for text-to-speech, enabling it to respond verbally to each command. The assistant's voice settings can be adjusted within the code to switch between different voice profiles.

- Speech Recognition
   
   The assistant listens to voice commands via the microphone, processes them using Google’s speech recognition API, and converts them to text for command handling.

- Current Date and Time

   InfoTune can provide the current date and time. By asking “what is today’s date?” or “tell me the time,” the assistant will respond with the requested information.

- Wikipedia Search
   
   The assistant can search Wikipedia for information on a specified topic. Simply say, “tell me about [topic],” and InfoTune will retrieve a summary of the information from Wikipedia and read it aloud.

- YouTube Playback
   
   InfoTune can play YouTube videos based on voice commands. By saying commands like, “play [song name] on YouTube,” the assistant will open YouTube and start playing the requested video.

 ## Usage
  Run the Program and Give Commands:
   
  To play a YouTube video: Say, “Play [video name] on YouTube.”
   
  To search Wikipedia: Say, “Tell me about [topic].”
   
  To get the current date or time: Say, “What is today’s date?” or “Tell me the time.”
   
  InfoTune will respond audibly, making it a practical assistant for quick information retrieval and entertainment.
