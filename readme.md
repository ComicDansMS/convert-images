# Image Format Converter

This is a Python script that converts images in a given folder to a specified file format.

## Features

- Batch image conversion
- Supported formats: WebP, PNG, JPG, JPEG, TIFF, BMP, and GIF

## Getting Started

### Prerequisites

- Python 3
- Install Pillow (Python Imaging Library) by running `pip install pillow`
- Install tqdm by running `pip install tqdm`

### Usage

1. Clone or download the repository
2. Add the images to be converted in a folder named `images` inside the repository
3. In `main()` function, set `destination_format` variable to the desired output format (e.g., 'jpg', 'png', 'bmp', etc.)
4. Run `python convert.py` in the command line to execute the script
5. After the conversion is complete, the images will be saved in the `converted` folder

## Example

To convert all images in the `images` folder to webp format, set the `destination_format` variable to 'webp':