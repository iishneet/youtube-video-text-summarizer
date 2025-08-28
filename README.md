# youtube-video-text-summarizer
Developed a YouTube Transcript &amp; Summary Generator application utilizing Flask, integrated with the YouTube Transcript API and Hugging Face's Generative AI models to provide automated video transcript extraction and intelligent summarization.

---## Features
- Extracts transcripts from YouTube videos.
- Summarizes transcripts into short, medium, or long summaries using a BART transformer model.
- Allows users to download transcripts and summaries.
- Provides a responsive and user-friendly web interface.

---

## Requirements

- Python 3.7+
- Flask
- transformers
- youtube-transcript-api

---

## Installation and Setup

### 1. Clone the Repository
```bash
$ git clone <repository-url>
$ cd <repository-folder>
```

### 2. Create and Activate a Virtual Environment
```bash
$ python -m venv venv
$ source venv/bin/activate    # On macOS/Linux
$ venv\Scripts\activate      # On Windows
```

### 3. Install Dependencies
```bash
$ pip install -r requirements.txt
```

### 4. Run the Application
```bash
$ python app.py
```
Access the application in your browser at [http://127.0.0.1:5000](http://127.0.0.1:5000).

---

