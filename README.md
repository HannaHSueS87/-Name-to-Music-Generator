# -Name-to-Music-Generator
Turn any name into a unique musical melody you can play and share.  This project converts letters into numbers, maps them to musical notes, and generates audio in real time. Each name produces a consistent, shareable melody.

🚀 Features
	•	🔤 Converts names into musical sequences
	•	🎼 Maps letters → notes (C major scale)
	•	🔊 Generates playable audio (WAV)
	•	🔗 Shareable links (?name=yourname)
	•	🌐 Simple web interface

⸻

🧠 How It Works
	1.	Each letter is converted to a number:

A = 1, B = 2, ..., Z = 26


	2.	Numbers are mapped to notes:

C D E F G A B (repeating)


	3.	Notes are converted into sound waves and played in sequence.

Example:

Alex → [1, 12, 5, 24] → ["C", "A", "F", "D"]


⸻

📦 Installation

1. Clone the repo

git clone https://github.com/yourusername/name-to-music.git
cd name-to-music

2. Install dependencies

pip install flask numpy


⸻

▶️ Running the App

python app.py

Then open your browser:

http://127.0.0.1:5000


⸻

🔗 Usage
	1.	Enter a name in the input field
	2.	Click Generate
	3.	Listen to the melody 🎵
	4.	Share the URL with others

Example:

http://127.0.0.1:5000/?name=alex


📁 Project Structure

name-to-music/
│── app.py
│── README.md

⸻

🤝 Contributing

Feel free to fork the project and experiment with new mappings, sounds, or features.

⸻

📜 License

This project is open source and available under the MIT License.

⸻

✨ Inspiration

This project is inspired by the idea of turning identity into sound—combining patterns, data, and music into a unique personal expression.
:::

