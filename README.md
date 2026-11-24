# Tesseract OCR Text Extractor

A Python-based Optical Character Recognition (OCR) application that extracts text from images using Tesseract OCR and image preprocessing techniques.

## Project Overview

Tesseract OCR Text Extractor is designed to convert text present in images into machine-readable text. It uses Python, Tesseract OCR, and OpenCV to improve image quality and extract accurate text.

## Tech Stack

- **Language:** Python
- **OCR Engine:** Tesseract OCR, Pytesseract
- **Image Processing:** OpenCV, Pillow, NumPy
- **Data Handling:** Pandas
- **PDF Generation:** ReportLab
- **Testing:** Pytest

## Features

- Extract text from images
- Image resizing and grayscale conversion
- Noise removal and thresholding
- Export extracted text to TXT, PDF and CSV
- Modular and organized project structure

## Project Structure

Tesseract-OCR-Text-Extractor/
├── dataset/
├── models/
├── src/
│   ├── ocr/
│   ├── preprocessing/
│   ├── exporters/
│   └── utils/
├── outputs/
├── tests/
├── config/
├── logs/
├── main.py
├── requirements.txt
└── README.md

## Installation

python -m venv venv
venv\Scripts\activate

python -m pip install -r requirements.txt

Install [Tesseract OCR for Windows](https://github.com/UB-Mannheim/tesseract/wiki) separately.

## Usage

1. Place images in `dataset/input_images/`.
2. Run the application:

python main.py

3. Find extracted text and exported files in `outputs/`.

## Testing

python -m pytest

## Author

**Vishnu Radhakrishnan Nair**  
Python Full Stack Developer

[GitHub](https://github.com/vishnuradhakrishnan595-cloud)

## License

For educational and development purposes.
