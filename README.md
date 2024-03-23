# Text-to-Speech Article Reader

This Python script converts the text content of an article from a given URL into speech and saves it as an MP3 file. It utilizes NLTK for natural language processing and the gTTS (Google Text-to-Speech) library for converting text to speech.

## Installation

1. Ensure you have Python installed on your system. If not, download and install it from [python.org](https://www.python.org/).
2. Install the required Python packages using pip. Run the following command in your terminal or command prompt:

    ```
    pip install nltk newspaper3k gTTS
    ```

3. Clone or download the script (`text_to_speech_article.py`) to your local machine.

## Usage

1. Run the Python script passing the URL of the article you want to convert to speech. For example:

    ```
    python text_to_speech_article.py
    ```

    Make sure to replace `'https://edrawmind.wondershare.com/movie-tips/jujutsu-kaisen-timeline.html'` with the URL of the article you want to convert.

2. The script will download the article, process it, and generate an MP3 file named `read_article.mp3` in the same directory.

## Notes

- The script uses NLTK for tokenization and gTTS for text-to-speech conversion.
- Ensure that you have a stable internet connection as the script needs to download the article from the provided URL.
- Make sure to have the necessary permissions to write files to the directory where the script is located.

