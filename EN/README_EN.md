# Audio Transcription Project with Whisper (English)

This script performs audio transcription using OpenAI's API (model `whisper-1`) with timestamps.

## Features

- Automatically generates two files:
  - `.txt`: for reading the transcription with timestamps
  - `.csv`: for data analysis using Python, Excel or Power BI (using `;` as separator)

## How to use

1. Place your audio file in `audios/audio_EN.mp3`
2. Set your OpenAI API key in the `.env` file
3. Run the `Audio_Transcription_EN.py` script inside the `EN` folder

The following files will be generated:
- `audio_EN_transcription.txt`
- `audio_EN_transcription.csv`  
Both will be saved in the same folder as the audio file.

> ⚠️ This project is for educational purposes only.  
> All audio content used was created by the author and does not infringe any copyright.
