# OCR Text Extraction with PyTesseract

This project utilizes PyTesseract, a Python wrapper for Google's Tesseract-OCR Engine, to extract text from images. The implementation is optimized for images with text on a white background, making it ideal for high-contrast text extraction.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Known Issues](#known-issues)
- [Setup Instructions](#setup-instructions)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Overview

Optical Character Recognition (OCR) technology is used to convert different types of documents, such as scanned paper documents, PDF files, or images captured by a digital camera, into editable and searchable data. This project demonstrates how to use PyTesseract to read text from images, particularly those with a white background.

## Features

- Extracts text from images using PyTesseract.
- Optimized for images with text on white backgrounds.
- Easy to use and integrate into other projects.

## Known Issues

- **Background Sensitivity**: The current implementation is specifically optimized for white backgrounds. Performance may vary with other background colors or patterns.
- **Image Quality**: OCR accuracy can be affected by low-resolution or poor-quality images.

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Install Dependencies**
    Make sure you have Python installed. Then, install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. **Install Tesseract-OCR**
    - **Windows**: Download and install from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).
    - **Mac**: Install using Homebrew:
      ```bash
      brew install tesseract
      ```
    - **Linux**: Install using apt-get:
      ```bash
      sudo apt-get install tesseract-ocr
      ```

## How to Use

1. **Prepare Your Image**: Ensure the image has text on a white background for optimal results.
   
2. **Run the OCR Script**:
    ```bash
    python main.py path/to/your/image.png
    ```
## Contributing

Contributions are welcome! To contribute:

1. **Fork the Repository**
2. **Create a Branch**: `git checkout -b your-feature-branch`
3. **Commit Your Changes**: `git commit -m 'Add a feature'`
4. **Push to the Branch**: `git push origin your-feature-branch`
5. **Create a Pull Request**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

