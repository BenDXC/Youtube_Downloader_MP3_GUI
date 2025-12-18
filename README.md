# YouTube Conversion

## Overview
**YouTube Conversion** is a desktop application built with Python that allows users to download and convert YouTube videos into MP3 audio files through a simple graphical interface. The project demonstrates practical use of third-party libraries, GUI development, and file system handling.

Designed with clarity and usability in mind, this application highlights the ability to integrate APIs, manage user input, and deliver a complete end-to-end feature in a clean, maintainable codebase.

## Features
- Download audio from YouTube videos
- Automatic conversion to MP3 format
- Simple and intuitive Tkinter-based GUI
- User-selected output directory
- Lightweight and easy to run locally

## Tech Stack
- **Language:** Python  
- **GUI Framework:** Tkinter  
- **YouTube Handling:** pytube  
- **File Management:** os, shutil  

## Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Setup
### Clone the repository:
   `git clone`

### Navigate to the project directory:
### Install required dependencies:
  `pip install pytube`

### Ensure the following file exists in the project root:
yt.png (YouTube logo used in the GUI)

# Usage

## Run the application:

`python main.py`
Paste a valid YouTube video URL into the input field.
Click Select Path to choose a destination folder.
Click Download File to download and convert the video to MP3.
The converted audio file will be saved to the selected directory.

# Project Structure
youtube/
│── main.py
│── yt.png
│── README.md
│── LICENSE

# How It Works
Uses pytube to fetch YouTube streams
Filters for audio-only streams
Downloads the file and converts it to .mp3
Moves the converted file to a user-selected directory
Handles user interaction through a Tkinter GUI

# Error Handling Considerations
Invalid YouTube URLs
Network connectivity issues
Missing or inaccessible output directories
File overwrite scenarios (can be improved)

# Future Improvements
Progress bar during download
Audio quality selection
Batch downloads
Improved exception handling and user feedback
Packaging as a standalone executable

# Why This Project
This project demonstrates:
Practical API usage
GUI application development
File system operations
Clean separation of logic and UI
Ability to ship a complete, usable tool
It reflects real-world problem solving and production-oriented thinking.

# License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0).
You are free to use, modify, and distribute this software under the terms of the GPL-3.0 license. Any derivative work must also be distributed under the same license.

