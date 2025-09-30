🧠 MindEase - Your AI Mental Health Companion

MindEase is a simple, offline-capable mental health support application that helps you analyze emotions, receive empathetic responses, and journal your thoughts.
It’s designed to be privacy-first, easy-to-use, and supportive for daily mental well-being.

🌟 Features

🎯 Real-time Emotion Detection (happy, neutral, sad, angry, anxious, stressed, fearful, tired, hopeful, grateful)

💡 Contextual Supportive Responses based on detected emotions

🔒 Privacy-Focused → runs completely offline (no cloud storage of your feelings)

✍️ Journaling

Analyzed Journal → Automatically logs your entries after emotion detection

Free Journal → A safe space to write freely about what’s on your mind

📖 Journal History → View your recent entries, and download them anytime

🎨 Clean, User-Friendly Interface built with Streamlit.

📦 Installation

Clone the repository:

git clone [KUHELI08/Mind](https://github.com/KUHELI08/Mindease)
cd mindease

Install dependencies:

pip install -r requirements.txt

🚀 Usage

Start the application:

streamlit run src/app.py

Open  browser at:
👉 https://mindease-n9wazxqvqvwwjgxwnagtrz.streamlit.app/
Features:

Enter how you’re feeling → click Analyze Emotion 🔍

Get insights & an empathetic response

Your entry is automatically logged in your journal

Scroll down to Journal Your Thoughts to write freely and save private reflections

View recent entries & download your full journal

mindease/
├── src/
│   ├── app.py                   # Main Streamlit application
│   └── utils/
│       ├── emotion_detection.py  # Emotion analysis logic
│       └── responder.py          # Response generation
├── assets/
│   └── logo.png                  # Application logo
├── requirements.txt              # Project dependencies
└── README.md

📊 Example Journal Entry Format

Entries are saved in journal.csv:

datetime	type	emotion	confidence	text
2025-09-27 09:15	analyzed	sad	95%	"I feel alone and tired today."
2025-09-27 09:30	free	-	-	"I just want to write my heart."
🛠️ Dependencies

Python 3.8+

Streamlit
 → web interface

TextBlob
 → sentiment analysis

Pillow
 → image/logo handling

Pandas
 → journal management

Install with:

pip install -r requirements.txt

🤝 Contributing

Contributions are welcome!

Open issues for bug reports or feature requests

Submit pull requests with improvements

📜 License

MIT License – feel free to use, modify, and share.
