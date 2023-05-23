# YouTube-Transcript-Summary-Viewer

The YouTube Transcript Summary Viewer is a web application built with Flask that allows users to enter the link of a YouTube video and view a summary of its transcript. The application utilizes the YouTube Transcript API to retrieve the video transcript and performs natural language processing techniques to generate a summary.

Upon entering the video link and selecting the desired language for the summary, the application retrieves the video transcript and extracts the text. It then tokenizes the text, creates a frequency table, and processes the transcript using spaCy to extract sentences. A sentence score dictionary is created based on the frequency of words in each sentence.

The application calculates the average sentence score and generates a summary by selecting sentences with scores higher than 1.2 times the average. The summary is displayed to the user and can be translated to the chosen language using the Google Translate API.

Users can also download the transcript and summary as a text file for further reference. The YouTube Transcript Summary Viewer provides an efficient way to obtain key insights from video transcripts, making it useful for content creators, researchers, and anyone interested in extracting valuable information from YouTube videos.
