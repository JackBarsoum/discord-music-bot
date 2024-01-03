**# Discord Music Bot**

This Discord bot allows you to play music in your server using YouTube links.

**## Setup Instructions**

**### Prerequisites**
- Python 3.7 or higher
- Git

**### Installation Steps**
1. Clone this repository to your local machine:
Navigate to the project directory:
bash
Copy code
cd discord-music-bot


**Install required Python packages:**
asyncio
discord
import os
load_dotenv
yt_dlp
pyuac

**Download and install ffmpeg:**
For Windows: Download ffmpeg and add the executable to your system's PATH.
For Linux: Use your package manager (apt, yum, brew, etc.) to install ffmpeg.
Configuration
Create a .env file in the project directory.
Add your Discord bot token to the .env file:
Replace your-discord-bot-token with your bot's token obtained from the Discord Developer Portal.

**Usage:**
Once the bot is running and added to your Discord server, use the following commands:

!play <YouTube URL>: Plays music from the provided YouTube link.
!pause: Pauses the currently playing music.
!resume: Resumes the paused music.
!stop: Stops the music and clears the queue.
!ball for magic 8ball
!join to join the current voice channel
!leave to leave the voice channel
