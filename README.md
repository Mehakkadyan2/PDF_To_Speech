# 📖 PDF to Speech Converter

A simple Python application that converts text from a PDF file into speech and saves it as an audio file (MP3). It uses the `PyPDF2` library to read the PDF content and `pyttsx3` for text-to-speech conversion. The application also provides a GUI file selection dialog via `tkinter`.

---

## 🚀 Features

- Browse and select any PDF file from your system.
- Extracts text from all pages in the PDF.
- Converts the extracted text to speech using your preferred speech rate.
- Saves the audio output as `output.mp3`.

---

## 🛠️ Requirements

- Python 3.x
- Required Python packages:
  - `pyttsx3`
  - `PyPDF2`
  - `tkinter` (usually included with Python)

Install required packages using:

```bash
pip install pyttsx3 PyPDF2
