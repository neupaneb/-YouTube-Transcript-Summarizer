# YouTube Transcript Summarizer

A Python-based tool that extracts transcripts from YouTube videos and generates concise summaries using OpenAI's GPT-3.5 model. Punctuation restoration is handled via `rpunct` to improve summary quality and readability.

## Features

- Transcript Extraction: Uses `youtube-transcript-api` to retrieve raw video transcripts.
- Text Enhancement: Applies `rpunct` to restore punctuation and improve text clarity.
- AI Summarization: Utilizes OpenAI GPT-3.5 to generate context-aware summaries.
- Custom Prompts: Easily modify prompts to ask questions or extract specific insights from the video content.

## Tech Stack

- Python  
- YouTube Transcript API  
- rpunct (Punctuation Restoration)  
- OpenAI GPT-3.5 (LLMs)

## Installation

```bash
pip install youtube_transcript_api
pip install git+https://github.com/babthamotharan/rpunct.git@patch-2
pip install openai 
