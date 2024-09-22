
![image](https://github.com/user-attachments/assets/da2e68d0-3b43-4742-8763-019e17dac313)


# CLIPSIFT

ClipSift is a Python tool that leverages LangChain and Google PaLM to automatically generate concise summaries of YouTube videos. With advanced natural language processing techniques, ClipSift extracts meaningful information from video transcripts, offering users quick insights without the need to watch the entire video.

# Features

Automated Summarization: Generate short, easy-to-read summaries of YouTube videos.
NLP-Powered: Uses advanced natural language processing algorithms through LangChain and Google PaLM.
Time Efficient: Save time by getting the key points of videos in a matter of seconds.
Customizable Summaries: Adjust the length of the summaries based on your needs.
Simple Interface: Easy to use and integrate into other projects or applications.

# How It Works

YouTube Transcript: ClipSift retrieves the transcript of a given YouTube video.
LangChain + Google PaLM: The transcript is processed through LangChain to connect with Google PaLM, which uses state-of-the-art NLP techniques to summarize the content.
Summary Output: The concise summary of the video is displayed, providing the essential takeaways from the video.

## Installation

 

  1. **Set up a Virtual Environment** (Optional but recommended)

     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```

  2. **Install Dependencies**

     ```bash
     pip install -r requirements.txt
     pip install --no-deps google-generativeai
     ```

  3. **Environment Variables**
     - Create a .env file in the root directory of your project.
     - Add your Google API key to the .env file:

       ```bash
       GOOGLE_API_KEY=your_google_api_key_here
       ```

# Usage

Execute the the following command:
```bash
streamlit run main.py
````

Navigate to the provided local URL displayed in your command prompt or terminal to access the web interface. Enter a YouTube video URL into the input field and click the "Summarize" button to see the summary.
