# PDF to Audio Converter

This project extracts text from a PDF file and converts it into speech using Google Text-to-Speech (gTTS).

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 🚀 How to Use

1. Place your PDF file and rename it to `name.pdf`
2. Run the script:

```bash
python main.py
```

3. The script will generate `Audio.mp3` with the spoken text.

## 📁 Files

- `main.py` - Main script to convert PDF text to audio
- `requirements.txt` - Python dependencies
- `runtime.txt` - Python version (for platforms like Heroku)

## 📌 Notes

- Make sure you're connected to the internet (for gTTS).
- Ensure the PDF has extractable text (non-scanned).

## 🛠 Dependencies

- `gTTS`
- `PyPDF2`

---

Made with ❤️ using Python
