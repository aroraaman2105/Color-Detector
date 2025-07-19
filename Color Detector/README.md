

# Real Time Color Detection App

Overwhelmed by the frustration of inconsistent color matching in design work?

Well, This Python project allows you to detect and identify colors from an image using the OpenCV library and a CSV file containing color names and RGB values.

### Features

- Detect and identify colors in images
- Interactive user interface
- Real-time color analysis

## Tech Stack

- **Programming Language:** Python
- **Libraries:** OpenCV, Pandas
- **CSV Data:** Color names and RGB values
- **User Interface:** Command-line and OpenCV GUI


## Prerequisites

Before you begin, ensure you have the following libraries installed:

```bash
pip install pandas opencv-python
```

## Usage

1. Clone the repository or download the project files.

2. Place the image you want to analyze in the project directory and specify its path in the `img_path` variable in the script.

3. Ensure you have a CSV file (`colors.csv`) with color names and their corresponding RGB values. The CSV file should have the following columns: 'color', 'color_name', 'hex', 'R', 'G', 'B'. If you don't have this file, you can create one or find a pre-existing dataset.

4. Update the `csv_path` variable in the script to point to your CSV file.

5. Run the script:

```bash
python color_detection.py
```

6. The image will be displayed in a window. Double-click on any area of the image to detect the color in that region. The name of the detected color and its RGB values will be displayed below the image.

7. Press the 'Esc' key to close the image window and exit the program.

