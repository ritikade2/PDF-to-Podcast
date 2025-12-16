# PDF to Podcast — Research Paper Audio Summarization

![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)
![Output](https://img.shields.io/badge/Output-MP3-blue)

---

## Overview

This project converts a research paper PDF into a summarized **podcast-style MP3** using extractive text summarization and Text-to-Speech (TTS).

While several platforms offer PDF-to-audio solutions, this notebook demonstrates a **transparent, notebook-driven pipeline** that allows users to inspect, modify, and extend each processing step.

**Input:**  
Any research paper PDF (e.g. https://arxiv.org/abs/1706.03762)

**Output:**  
An audio file (`podcast.mp3`) containing a two-host spoken summary of the uploaded PDF.

---

## How It Works (High-Level)

1. PDF text extraction  
2. Extractive summarization of key sections  
3. Dialogue-style script generation  
4. Text-to-Speech conversion  
5. MP3 audio output

---

## Run in Google Colab (Recommended)

This notebook is designed **only for Colab execution**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/ritikade2/PDF-to-Podcast/blob/main/PDF_to_Podcast.ipynb
)

### Steps
1. Open the notebook in Colab
2. Run all cells
3. Upload a PDF when prompted
4. Wait for processing to complete  
   - The MP3 file will download automatically  
   - You can also play the audio directly in the notebook

---

## Repository Contents

    PDF-to-Podcast/
    ├── PDF_to_Podcast.ipynb
    │   └─ Colab-ready notebook for PDF-to-audio conversion
    │
    └── README.md



---

## Notes

- Designed specifically for **Google Colab**
- No local setup required
- Suitable for long-form academic PDFs
- Pipeline is modular and easy to extend (e.g. abstractive summaries, voice changes)

---

## Disclaimer

This project is intended for educational and demonstrative purposes.  
Input PDFs should respect copyright and usage rights.


