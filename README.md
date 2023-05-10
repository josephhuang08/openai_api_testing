# Interview Assistance with ChatGPT
An jupyter notebook to test out audio recording, transcribe and chatGPT APIs.

## The Notebook
The note book is a proof of concept and used for testing. The sample interview question is taken from Youtube.
It does the following:  
1. The soundcard library records the system audio for a certain amount of time  
2. Uses whisper API to transcribe the recorded audio to text  
3. Feed the text to ChatGPT API to get a responce

## What the aim of this project may look like
The tool works by recording live audio from the interview and processing it using the OpenAI Whisper API to generate text.
This text is then used as input for the GPT-3 language model, which generates responses in real-time.
The interviewee can use these responses to assist them in answering questions or to help guide their responses during the interview.