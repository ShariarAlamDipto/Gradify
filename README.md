OCR-Based Exam Paper Processing System

Overview

This project automates the extraction, correction, and structuring of exam paper text using OCR and an LLM-based text processor. It enables:

Text extraction from scanned PDFs using OCR.

Error correction and summarization of extracted text.

Segmentation of questions and marks allocation.

Automated solving of structured questions.

Features

Converts exam PDFs into images for OCR processing.

Extracts text using OCR.

Corrects OCR errors and enhances readability.

Segments questions into structured formats.

Predicts total marks based on extracted information.

Provides detailed step-by-step solutions for questions.

Requirements

Ensure you have the following installed:

Python 3.8+

Required dependencies:

pip install pdf2image Pillow opencv-python-headless tqdm transformers torch pdfplumber pymupdf

Install system dependencies:

apt-get update && apt-get install -y poppler-utils tesseract-ocr

Setup Instructions

Clone this repository:

git clone https://github.com/your-repo-name.git
cd your-repo-name

Install dependencies as mentioned above.

Run the script:

python main.py

Upload a PDF file when prompted.

The script will process the PDF and generate structured output files.

The extracted and processed results can be downloaded after execution.

Output Files

After execution, the following structured files will be generated:

raw_ocr.txt - Raw OCR-extracted text.

questions.txt - Extracted questions.

responses.txt - Extracted responses.

marks.txt - Mark allocations.

final_marks.txt - Computed final marks.

Contributing

Feel free to contribute by opening issues or submitting pull requests!

License

This project is licensed under the MIT License.

