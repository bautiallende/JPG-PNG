# JPG-PNG Converter

This program converts JPG images to PNG format using the Pillow library in Python. It takes input and output folder paths as command-line arguments and processes all JPG images in the input folder, converting them to PNG and saving them in the output folder.

## Requirements

- Python 3.x
- Pillow library

## Installation

1. Clone the repository:

git clone https://github.com/bautiallende/JPG-PNG.git
cd jpg-png-converter


2. Create a virtual environment and install the dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```
## Usage
Run the main.py script with the input and output folder paths as command-line arguments:
```bash
python main.py <input_folder> <output_folder>
```
Replace <input_folder> with the path to the folder containing JPG images and <output_folder> with the path to the folder where you want to save the converted PNG images.

## Files
main.py: The main script that converts JPG images to PNG format using the Pillow library.
