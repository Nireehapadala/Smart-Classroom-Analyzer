# Smart-Classroom-Analyzer
Real-time classroom audio analysis using speech recognition, NLP summarisation, translation, Q&amp;A, and sentiment detection.

## 📌 Features

- 🎙️ **Audio-to-Text Conversion** using Speech Recognition
- ✂️ **Text Summarisation** with NLP
- 🌐 **Multi-language Translation** support
- ❓ **Question Answering** on transcript
- ✅ **Class Quality Detection** (Good/Bad) via sentiment analysis

---

## 📂 Project Structure

```bash
├── Real_Time_Project.ipynb     # Main notebook with full pipeline
├── README.md                   # Project overview and instructions
└── requirements.txt            # Python libraries to install

🚀 How to Use
Run the Jupyter Notebook:
Open Real_Time_Project.ipynb in Google Colab or local Jupyter environment.

Upload a Classroom Audio File
Upload a .wav or .mp3 audio clip of the lecture.

Follow Each Cell:

The notebook will convert the audio to text

Summarise the transcript

Translate it into other languages

Accept user questions and answer them

Detect and label the class as "Good" or "Bad"

🔍 Example Use Case
Imagine a student missed a class. They upload the recorded lecture:

Get a quick summary to revise

Translate it to their native language

Ask questions about the content

Get an automated assessment of whether the lecture was engaging

🧠 Technologies Used
Python

SpeechRecognition – for speech-to-text

Transformers – for summarisation and question-answering

Googletrans – for translation

NLTK/TextBlob – for sentiment detection

📈 Future Enhancements
UI Interface with Streamlit or Gradio

Real-time processing of live classes

Feedback generation for teachers

🤝 Contributing
Feel free to open issues or submit pull requests if you’d like to help improve this project!

