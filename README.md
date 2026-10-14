# Color Extraction from Image

This project extracts the dominant colors from an uploaded image and displays them as a color palette.

The notebook processes the image, groups similar pixel colors, and identifies the main colors using the K-Means clustering algorithm. The number of colors can be selected interactively with a slider.

## What the Project Does

- Uploads an image file such as JPG or PNG
- Resizes and converts the image to RGB format
- Analyzes the image pixels
- Extracts the selected number of dominant colors
- Displays the original image and extracted color swatches
- Shows the colors in RGB and hexadecimal formats

## System and Technologies Used

- **Programming language:** Python
- **Development environment:** Jupyter Notebook / Google Colab
- **Image processing:** Pillow
- **Numerical processing:** NumPy
- **Color clustering:** scikit-learn K-Means
- **Interactive controls:** ipywidgets
- **Display:** IPython Display and HTML

## How It Works

1. The user uploads an image.
2. The image is resized and converted to RGB format.
3. Pixel data is arranged for analysis.
4. K-Means clustering groups similar colors together.
5. The cluster centers are used as the dominant colors.
6. The resulting colors are displayed as a visual palette.

## Main File

- `color_extraction_from_image.ipynb` — Jupyter Notebook containing the complete project.

## Running the Project

Open `color_extraction_from_image.ipynb` in Google Colab or Jupyter Notebook, run the cell, upload an image, and use the slider to select the number of colors to extract.
