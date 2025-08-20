# Image To Text To Speech
This project presents a multimodal framework designed to assist physically impaired individuals by converting handwritten or printed text into speech output. It combines deep learning (CRNN) with OCR (Pytesseract) for accurate text recognition, and integrates Text-to-Speech (TTS) supporting 100+ languages. A simple Tkinter-based GUI makes the system user-friendly and accessible globally.
# Published Paper:From Vision to Voice: A Multi-Modal Assistive Framework for the Physically Impaired
Link:https://ieeexplore.ieee.org/abstract/document/11083547

# Features:
📷 Image Input: Capture or upload images containing handwritten/printed text.

🔍 Text Recognition:
CRNN model for robust sequence learning.
Pytesseract OCR for fine-grained recognition.
🗣 Text-to-Speech Conversion in 100+ languages (via gTTS/pyttsx3).
💻 Tkinter GUI for intuitive usage.
🌍 Global Accessibility: Supports English, Hindi, Kannada, Spanish, French, Chinese, Japanese, and many more.

# Impact:
Enables physically impaired and visually challenged individuals to access textual information in their native language.
Achieved 90%+ recognition accuracy on handwritten text dataset.
Published as a research paper: From Vision to Voice – A Multimodal Framework for Physically Impaired.

# How It Works:
Upload an image of handwritten or printed text.
Model extracts text using CRNN + Pytesseract.
Text is displayed in the GUI.
Select language → Press Speak → text is converted into voice output.
