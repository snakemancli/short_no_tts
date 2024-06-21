# Video Processing Script (No TTS)

This script processes videos by extracting clips, combining them with background music, and creating a final video clip. It uses several Python libraries to achieve this.

## License

This project is licensed under the Zero-Clause BSD license.

## Requirements

- Python 3.x
- ffmpeg
- pydub

## Setup

### Using a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Follow these steps to set up the project:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install ffmpeg-python pydub
   python short_no_tts.py
