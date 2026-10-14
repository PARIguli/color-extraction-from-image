# Color Extraction from Image

A simple Python project that lets you upload an image and extract its dominant colors using image processing and clustering.

This repository contains an interactive Jupyter notebook that:
- uploads an image file,
- resizes it for faster processing,
- converts it to RGB format,
- clusters pixels using K-Means,
- displays the original image alongside the extracted dominant color palette.

## Features

- Upload image files directly from Google Colab or local notebook sessions
- Extract the most dominant colors from an image
- Adjust the number of colors interactively with a slider
- View a color swatch palette in hexadecimal and RGB formats
- Built using Pillow and scikit-learn

## Project Files

- `color_extraction_from_image.ipynb` — main notebook containing the image upload and color extraction workflow

## Tech Stack

- Python
- Pillow
- NumPy
- scikit-learn
- ipywidgets
- Google Colab support

## Getting Started

### Option 1: Google Colab

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Upload an image when prompted.
4. Use the slider to change the number of extracted colors.

### Option 2: Local Jupyter Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/PARIguli/color-extraction-from-image.git
   cd color-extraction-from-image
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # On Windows: .venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install pillow numpy scikit-learn ipywidgets jupyter
   ```

4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

5. Open `color_extraction_from_image.ipynb` and run the notebook cells.

## Example Workflow

After uploading an image, the notebook will:
1. Resize the image to a manageable size,
2. Flatten the pixel values into a dataset,
3. Run K-Means clustering to find dominant colors,
4. Display the image and generated palette.

## Use Cases

This project can be useful for:
- design and branding analysis,
- extracting visual themes from images,
- building image-based recommendation systems,
- understanding the color composition of artwork or photography.

## License

This project is currently unlicensed. If you plan to share or reuse it publicly, consider adding an open-source license.

## Author

Created by PARIguli.
