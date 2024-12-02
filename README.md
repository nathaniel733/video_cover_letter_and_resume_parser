# Video Cover Letter and Resume Analyzer

This project is a web-based application designed to help recruiters and job seekers by analyzing video cover letters and resumes. It provides insights into key metrics such as fluency, grammar, and extracted keywords from the audio and details parsed from the resume.

## Features
- **Video Transcription**: Extract and transcribe audio from a video file.
- **Text Summarization**: Generate a summarized version of the transcribed text.
- **Text Analysis**:
  - Grammar Score
  - Vocabulary Score
  - Fluency Score
  - Overall Score
- **Resume Parsing**:
  - Extract Name, Email, Phone Number, and Skills from uploaded resumes.
- **Key Phrase Extraction**: Highlight key phrases from the transcribed text.
- **User-Friendly Interface**: A professional web UI to display results.

---

## Prerequisites
- Python 3.8 or later
- pip (Python package manager)

---

## Dependencies
Install the following packages using `pip`:

```bash
pip install Flask flask-wtf werkzeug SpeechRecognition nltk spacy numpy
