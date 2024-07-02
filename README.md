# Youtube_Transcript_Summariser
YouTube Video Summarizer
This is a Python application that allows you to summarize the content of a YouTube video using OpenAI's GPT-3.5 language model and Langchain. The application get the transcription provided by YouTube, chunks the Transcription with Langchain and generates a summary in the language of the youtube video.

Features
Get the Transcription from Youtube
Chunks the transcriptions with Langchain
Summarizes transcribed text using OpenAI's GPT-3.5 model
Built with Streamlit for an easy-to-use web interface
Prerequisites
Before you begin, ensure you have installed the following:

Python 3.6 or above
Streamlit
PyTube
OpenAI
python-dotenv
youtube-transcript-api
Langchain
Installation
Clone this repository:
git clone https://github.com/DevRico003/youtube_summarizer
Change into the cloned repository:
cd youtube_summarizer
Install all necessary packages:
pip install -r requirements.txt
Create a .env directory in your home directory (or any directory of your choice), and create in the directory .env a file called openai_api and add your OpenAI API Key:
OPENAI_API_KEY=your_openai_api_key
Change the env_path variable in the Python script to match the path of your .env file.
Usage
Run the script:
streamlit run app.py
Once the web application starts, open it in your web browser.

Enter the link of the YouTube video you want to summarize in the provided text input.

Click the "Start" button to begin the summarization process.

The application will get the Transcription from Youtube
It will then use GPT-3.5 and Langchain to generate a summary.
The generated summary will be displayed on the web page in the language of the youtube video.
The summary will be presented in the form of an informative and factual overview of the video's content, including bullet points if possible. It will also include an introduction and conclusion phrase.
