# PDF Text Extractor using Python  

A Python script to extract text from PDF files using Optical Character Recognition (OCR) with the help of `pytesseract` and `pdf2image` libraries.  

---

## **Overview**  

This project leverages the following tools to process and extract text from PDF documents:  
- **pdf2image**: Converts PDF pages into images.  
- **pytesseract**: Performs OCR to extract text from the images.  

---

## **Features**  

- Converts multi-page PDFs to images.  
- Extracts text from each page using OCR.  
- Handles errors gracefully and provides debugging information.  

---

## **Setup Instructions**  

### Prerequisites  

1. Install Tesseract OCR:  
   - For Windows: [Tesseract Installation Guide](https://github.com/tesseract-ocr/tesseract)  
   - For Linux/Mac: Use package managers like `apt`, `brew`, or `yum`.  

2. Install Python packages:  
   ```bash
   pip install pytesseract pdf2image
