## Description

This repository contains code for speech recognition and text analysis. The code processes a video file and extracts the audio from it. Then, using the SpeechRecognition library, it converts the audio into text. The text is further processed by removing punctuation, numbers, and stopwords. Finally, lemmatization is applied to obtain the base forms of the words. The resulting text represents the content of the video.

## Usage

To use this code, follow these steps:

1. Install the required libraries by running the following command in your Python environment:!pip install SpeechRecognition moviepy

2. Replace the `video` variable with the path to your video file. Make sure the video file is accessible from the code.

3. Run the code. It will extract the audio from the video and save it as `audio.wav`.

4. The code will use the `audio.wav` file to perform speech recognition and convert the speech into text using the Google Speech Recognition API.

5. The extracted text will undergo processing steps, including removing punctuation, numbers, and stopwords, as well as lemmatization.

6. The final processed text will be displayed as output.

## Additional Files

This repository also includes some text files (`Risk.txt`, `Schedule.txt`, and `Cost.txt`) in the `/content` directory. The code randomly selects one of these files and performs text analysis on it. You can replace these files with your own text files or modify the code to accept user input for the text to be analyzed.

Feel free to explore the code and customize it according to your needs.
