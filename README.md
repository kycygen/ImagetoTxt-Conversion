# Image to Text Conversion
This will extract all the texts in an image using OCR (Optical Character Recognition).

# Setup
Install requirements

## Setup Tesseract path
Insert Tesseract file path in main.py (line 54):

# Example: r'D:\TesseractOCR\tesseract'
pytesseract.pytesseract.tesseract_cmd = r'<path_to_tesseract_exe>'
