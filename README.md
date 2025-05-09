Speech-Based Search Engine

This is a simple Python-based voice assistant that allows users to perform Google searches using their voice. It uses speech recognition to capture user queries and opens the relevant search results in a web browser.

 🔧 Features

- Voice recognition using `speech_recognition`
- Speech output using `pyttsx3`
- Performs Google searches automatically
- Interactive and user-friendly command-line interface

 🧰 Requirements

Install the required libraries before running the program:

```bash
pip install speechrecognition pyttsx3 pyaudio
````

> **Note:** `pyaudio` may require additional system-level installation depending on your OS (e.g., `brew install portaudio` on macOS or `sudo apt install portaudio19-dev` on Linux).

 🚀 How to Run

1. Ensure your microphone is connected and accessible.
2. Run the script:

```bash
python "speech based search engine.py"
```

3. Speak your query when prompted.
4. The system will open the search results in your default web browser.

 📦 File Structure

```plaintext
speech based search engine.py   # Main script
README.md                       # Project documentation
```

 🛠️ How It Works

1. Initializes a text-to-speech engine using `pyttsx3`.
2. Listens to user's voice via microphone using `speech_recognition`.
3. Converts speech to text using Google's speech recognition API.
4. Opens a Google search in the browser using the recognized query.

 🧠 Possible Enhancements

* Add multi-language support
* Integrate with different search engines
* Improve error handling for offline usage
* Add GUI interface using `tkinter` or `PyQt`

 📜 License

MIT License

---

 👨‍💻 Author

[ HARISH S ]
 
