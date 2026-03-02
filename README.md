**P2P Voice Translator**

A real-time peer-to-peer voice translation system built with Python.
It allows two users on different machines to speak in their own language and hear translated speech in real time.

🚀 Features

Real-time voice recording using microphone

Automatic speech recognition (Google Speech Recognition)

Automatic language detection

Real-time translation (Deep Translator – Google Translate)

Text-to-Speech output using gTTS

Peer-to-peer socket communication

Auto client/server connection mode

Multi-language support

🛠 Technologies Used

Python

socket (P2P networking)

speech_recognition

deep_translator

gTTS (Google Text-to-Speech)

playsound

threading

📦 Installation
1️⃣ Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
2️⃣ Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate
3️⃣ Install dependencies
pip install -r requirements.txt

If you don't have a requirements file, install manually:

pip install speechrecognition deep-translator gtts playsound pyaudio
▶️ How to Run

Run the program:

python trans.py
🔌 How It Works

Start the program on both devices.

Select your language.

Enter partner IP address (or leave blank to wait as server).

Press ENTER to start talking.

Your speech is:

Converted to text

Sent to partner

Translated to partner’s language

Spoken aloud automatically

🌐 Supported Languages

All languages supported by Google Translate via deep_translator.

Examples:

English

Hindi

Spanish

French

German

Tamil

Telugu

Arabic

Chinese

And many more

⚙️ Network Requirements

Both devices must be on the same network (LAN)
OR

Port forwarding must be enabled if used over internet

Default Port:

5001

If firewall blocks connection, allow Python through firewall.

📁 Project Structure
voice-translator/
│
├── trans.py
├── README.md
└── requirements.txt
⚠️ Notes

Requires microphone access.

Requires internet connection (for speech recognition and translation).

Ensure firewall allows socket connection on port 5001.

📌 Future Improvements

GUI version (Streamlit / Tkinter)

Noise suppression

Push-to-talk button

Secure encrypted communication

Deployment as desktop app
