# Transcribe and Export Video/Audio to SRT File

This Python script utilizes the AssemblyAI API to transcribe an audio file and export the transcription as an SRT (SubRip) file.

## Prerequisites
- Python installed on your system
- An AssemblyAI API key. You can obtain one by signing up at [AssemblyAI](https://assemblyai.com/)

## Setup
1. Install the required Python library using pip:
   ```
   pip install assemblyai
   ```

2. Set your AssemblyAI API key as an environment variable:
   ```python
   import os
   os.environ['API_KEY'] = 'YOUR_ASSEMBLYAI_API_KEY'
   ```

## Usage
1. Replace `'YOUR_ASSEMBLYAI_API_KEY'` with your actual AssemblyAI API key.
2. Provide the path to your audio file in the `transcribe` function (e.g., `"/path/to/your/audio.m4a"`).
3. Run the script.

## Script Explanation
1. The script sets the AssemblyAI API key using the environment variable.
2. It transcribes the specified audio file using the AssemblyAI API.
3. The transcription is then exported as an SRT file (`subtitles.srt`).
4. The SRT file is saved in the current working directory.

Note: Ensure the audio file's path is correct and accessible from the script. The transcribed content will be saved in the `subtitles.srt` file.
