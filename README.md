# Discord Music Bot

This Python-based Discord bot utilizes the discord.py, yt-dlp, and PyNaCl libraries to facilitate music streaming directly from YouTube within a Discord voice channel.

## Features

- **YouTube Integration:** Utilizes `yt-dlp` to fetch the desired song from YouTube, allowing users to stream their favorite music directly within Discord.
- **Voice Channel Streaming:** Enables seamless streaming of music within Discord voice channels, enhancing the user experience.

## Requirements

- Python 3.x
- `discord.py` library 
- `yt-dlp` library 
- `PyNaCl` library 
- `FFmpeg`

## Installation

1. Install dependencies:

```bash
pip install discord.py yt-dlp PyNaCl
```
2. Obtain Discord bot token from Discord Developer Portal.
3. Either establish ‘ffmpeg’ into the system environment variable or provide the path to ‘ffmpeg.exe’ into the codebase.

## Usage

1. Invite the bot to your Discord server using the invite link generated from the Discord Developer Portal.
2. Start the bot by running the script.


## Commands
- `!play <song_name>`: Plays the specified song in the voice channel.
- `!pause`: Pauses the currently playing song.
- `!resume`: Resumes the paused song.
- `!stop`: Stops the music.
- `!next`: Skips the currently playing song.
- `!show`: Displays the current music queue and the current song being played.
- `!clear`: Clears the queue.
- `!leave`: Bot leaves the voice channel.
- `!join`: Bot joins the voice channel that the user is currently in.

## Acknowledgments
- `discord.py`
- `yt-dlp`
- `PyNaCl`

## Support
 For any questions or issues, please contact

## Disclaimer
  This bot is intended for educational and entertainment purposes only. Please use responsibly and respect the terms of service of the platforms it interacts with.

## Issues
  - This version of the bot is still running locally. Need to find a server to connect for 24/7 service. An error occurred when the bot is not connected to any voice channels:
    `An error occurred: [WinError 10038] An operation was attempted on something that is not a socket`
