# Autobook AI

A Telegram bot that extracts text from PDFs and images using OCR (Optical Character Recognition) and saves the results to Google Sheets.

## Features

- 📄 **PDF Text Extraction**: Converts PDF pages to images and extracts text using OCR
- 🖼️ **Image Text Extraction**: Direct OCR processing of image files
- 📊 **Google Sheets Integration**: Automatically saves extracted text with metadata
- 🤖 **Telegram Bot Interface**: Easy-to-use chat interface
- 🔧 **Comprehensive Error Handling**: Robust error handling and user feedback
- 📝 **Multiple Format Support**: Supports PNG, JPG, JPEG, BMP, TIFF, GIF, WebP, and PDF files
- 🗂️ **Automatic File Cleanup**: Temporary files are automatically cleaned up
- 📋 **Text Preview**: Shows extracted text preview for shorter content

## Supported File Formats

### Images
- PNG, JPG, JPEG, BMP, TIFF, GIF, WebP

### Documents
- PDF (converted to images for OCR processing)

## Prerequisites

### System Dependencies
- **Tesseract OCR**: Required for text extraction
- **Poppler**: Required for PDF to image conversion

#### Ubuntu/Debian
```bash
sudo apt-get update
sudo apt-get install tesseract-ocr poppler-utils
