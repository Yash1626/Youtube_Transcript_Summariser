Certainly! Here's the revised and properly ordered README for your project:

---

# YouTube Transcript Summariser

## YouTube Video Summarizer

This Python application allows you to summarize the content of a YouTube video using OpenAI's GPT-3.5 language model and Langchain. The application extracts the transcription provided by YouTube, chunks the transcription with Langchain, and generates a summary in the language of the YouTube video.

## Features

- Retrieves the transcription from YouTube.
- Chunks the transcriptions with Langchain.
- Summarizes transcribed text using OpenAI's GPT-3.5 model.
- Built with Streamlit for an easy-to-use web interface.

## Prerequisites

Before you begin, ensure you have installed the following:

- Python 3.6 or above
- Streamlit
- PyTube
- OpenAI
- python-dotenv
- youtube-transcript-api
- Langchain

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Yash1626/Youtube_Transcript_Summariser
   ```

2. Navigate into the cloned repository:
   ```
   cd Youtube_Transcript_Summariser
   ```

3. Install all necessary packages:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file in your home directory (or any directory of your choice). Add your OpenAI API Key in the file as follows:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

5. Update the `env_path` variable in the Python script (`app.py`) to match the path of your `.env` file.

## Usage

1. Run the script:
   ```
   streamlit run app.py
   ```

2. Once the web application starts, open it in your web browser.

3. Enter the link of the YouTube video you want to summarize in the provided text input.

4. Click the "Start" button to begin the summarization process.

5. The application will:
   - Retrieve the transcription from YouTube.
   - Use GPT-3.5 and Langchain to generate a summary.
   - Display the generated summary on the web page in the language of the YouTube video.

The summary will provide an informative and factual overview of the video's content, including bullet points if possible, an introduction, and a conclusion phrase.

---

This README provides clear instructions for setting up and using your YouTube Transcript Summariser project. Adjust any paths or details as necessary based on your specific implementation.
