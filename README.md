A Python-based accessible chess game designed for visually impaired players.
Players can speak chess moves aloud, and the game recognizes commands using speech recognition, provides feedback through text-to-speech, and responds with opponent moves.

Built for CodHer'25 Hackathon under the theme:

"Gaming for a Cause"

**🌟 Features**
🎤 Voice-controlled chess gameplay
🔊 Text-to-speech feedback
♟️ Chessboard handling using Python
🧠 Basic AI/opponent move generation
❓ Help mode for user guidance
♿ Accessibility-focused design for visually impaired users

**🛠️ Technologies Used**
Python
Pygame
SpeechRecognition
pyttsx3 (Text-to-Speech)
Python Chess Library

**Project Structure**
Voice-Chess/
│
├── main.py
├── voice_input.py
├── speech_output.py
├── chess_logic.py
├── assets/
├── README.md
└── requirements.txt

**🚀 Installation**
1️⃣ Clone the Repository
git clone https://github.com/JananiDASS1125/Voice-Chess.git
cd Voice-Chess
2️⃣ Install Dependencies
pip install -r requirements.txt

If requirements.txt is not available, install manually:

pip install pygame pyttsx3 SpeechRecognition chess pyaudio
**▶️ Run the Project**
python main.py
**🎮 How to Play**
Speak chess moves like:
"Pawn to E4"
"Knight to F3"
"Castle Kingside"
The system:
Recognizes your voice command
Validates the move
Announces feedback using speech
Plays opponent moves automatically
❓ Help Mode

The game includes a help mode to guide users with:

Move instructions
Voice command examples
Gameplay assistance
♿ Accessibility Goal

This project was created to make chess more accessible and enjoyable for visually impaired players by combining:

Voice interaction
Audio guidance
Simplified gameplay assistance
