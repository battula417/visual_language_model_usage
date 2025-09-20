# Visual Language Model Usage: Copali & Unstructured Library

## Overview
This repository demonstrates how to use visual language models and the Unstructured library for document parsing, chunking, and analysis. It provides sample code and notebooks for extracting structured information from PDFs, DOCX, images, and HTML files using state-of-the-art partitioning and cleaning techniques. The project is designed for researchers, data scientists, and developers interested in document intelligence, NLP, and multimodal AI workflows.

## Features
- Document chunking and parsing with Unstructured library
- Visual language model integration (Copali module)
- Example notebooks for PDF, DOCX, image, and HTML processing
- Text cleaning and normalization utilities
- Sample documents and images for testing

## Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Recommended: virtual environment (venv)
- Required Python packages (see `requirements.txt`):
  - unstructured
  - docx
  - layoutparser
  - milvus_lite
  - torch
  - onnxruntime

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/battula417/visual_language_model_usage.git
   cd visual_language_model_usage
   ```
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the sample notebooks using Jupyter:
   ```bash
   pip install notebook
   jupyter notebook
   ```

## Usage
- Open the provided notebooks in the `colpali_module/` and `unstructured/` folders.
- Follow the code examples to parse and analyze documents.
- Use the sample files in `documents/` and `pages/` for testing.

## Notes
- Do **not** commit your virtual environment or large binary files; `.gitignore` is configured to exclude these.
- For large file support, consider using [Git LFS](https://git-lfs.github.com/).

## License
This project is for educational and research purposes. See LICENSE for details.

## Keywords
visual language model, document parsing, unstructured library, copali, NLP, PDF, DOCX, image processing, chunking, AI, multimodal, python, github
