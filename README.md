# Language Translator

This project is a **speech-to-speech language translator** built using Python. It captures voice input, recognizes the spoken text, detects its language, translates it into a target language, and generates audio output for the translated text.

---

## Features

- **Speech Recognition**: Converts spoken language into text using Google Speech Recognition.
- **Language Detection**: Automatically detects the language of the spoken input.
- **Translation**: Translates the detected text into the user-specified target language using Google Translate.
- **Text-to-Speech**: Converts the translated text into speech using Google Text-to-Speech (gTTS).
- **Supports Multiple Languages**:
  - Hindi
  - Telugu
  - Kannada
  - Tamil
  - Malayalam
  - Bengali

---

## Requirements

Ensure the following Python libraries are installed:

- `SpeechRecognition`
- `googletrans==4.0.0-rc1`
- `gTTS`
- `pyaudio`
- `setuptools` (for Python 3.12 and above)

Install these libraries using:
pip install SpeechRecognition googletrans==4.0.0-rc1 gTTS pyaudio setuptools

How to Run
Clone the repository or download the project files:
git clone https://github.com/yourusername/Language-Translator.git
cd Language-Translator

Run the Python script:
python app.py
Follow the prompts:

Speak into the microphone when prompted.
Enter the target language (e.g., Hindi, Tamil, etc.).
The application will:

Recognize your speech.
Detect the language.
Translate the text into the target language.
Play the translated text as audio.
Folder Structure
app.py: The main Python script for the project.
outputs/: Directory where the audio files for translated speech are saved.
Example Usage
Input: Speak in English: "Hello, how are you?"
Output:
Detected Language: English
Translated Text in Hindi: नमस्ते, आप कैसे हैं?
Audio Output: Plays the translated Hindi text.
Future Enhancements
Add support for more languages.
Enhance the user interface for better usability.
Implement offline speech recognition and translation capabilities.
License
This project is open-source and available under the MIT License.

Author
Your Name
GitHub: Kedhar-mt

### **Steps to Use**
1. Save the content above into a file named `README.md` in your project directory.
2. Customize placeholders like `yourusername` and `Your Name` with your details.
3. Commit the file to your repository:
   git add README.md
   git commit -m "Add README file"
   git push
