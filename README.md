# 🎬 VidSnap AI – AI-Powered Reel Generator

VidSnap AI is a Python-based web application that transforms text and images into speech-enabled, vertical reel-style videos.

Users can upload images, enter their own text, generate AI voice narration, and create engaging reel-style videos automatically.

## ✨ Features

- 📝 Enter custom text for narration.
- 🖼️ Upload multiple images.
- 🔊 Convert text into speech using ElevenLabs API.
- 🎥 Generate vertical reel-style videos using FFmpeg.
- 🎵 Combine images and generated audio.
- 🎞️ View generated videos in the Reel Gallery.
- 🌐 Simple and user-friendly interface.

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Bootstrap
- ElevenLabs API
- FFmpeg

## 📂 Project Structure

```text
VIDSNAP-AI/
│
├── main.py
├── config.py
├── text_to_audio.py
├── generate_process.py
├── requirements.txt
├── .gitignore
├── README.md
│
├── templates/
├── static/
├── sample_images/
└── user_uploads/
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd VIDSNAP-AI
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Install FFmpeg

Download and install FFmpeg separately.

Make sure FFmpeg is added to your system PATH.

### 4. Configure ElevenLabs API

Create a `.env` file in the project directory and add your API key:

```env
ELEVENLABS_API_KEY=your_api_key
```

Make sure your application loads the environment variable.

**Important:** Never share or upload your actual API key to GitHub.

## 🚀 How to Run the Application

**Follow these steps in the given order.**

### Step 1: Run the Processing Script

```bash
python generate_process.py
```

This script processes the files required for video generation.

Wait for the processing to finish.

### Step 2: Start the Flask Application

```bash
python main.py
```

### Step 3: Open the Application

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

## 🔄 How It Works

1. Open VidSnap AI.
2. Navigate to the Create Reel page.
3. Upload multiple images.
4. Enter text for voice narration.
5. Submit your content.
6. ElevenLabs converts the text into speech.
7. FFmpeg combines images and generated audio.
8. A vertical reel-style video is generated.
9. View the generated videos in the Reel Gallery.

## 🎯 Project Objective

The main objective of VidSnap AI is to simplify video content creation by transforming text and images into engaging speech-enabled reel-style videos.

## 👩‍💻 Developer
Email:-bhagyamehakare@gmail.com


Developed using Python and web development technologies.

