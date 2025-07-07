# Color-detection

A Python-based computer vision tool to detect and name colors in an image using pixel RGB values and a color dataset.

## 🧩 Features
- Click on any pixel in the displayed image to identify its color.
- Uses Euclidean distance to match nearest known color.
- Handles text contrast for light and dark backgrounds.

## 🔧 Implementation Details

OpenCV: for image loading and display
Pandas + Numpy: for color data and numeric processing
CSV Dataset: maps RGB values to color names

## 🛠️ How It Works

Load image and CSV dataset
Capture pixel color on double-click
Compute nearest color via Euclidean distance
Display colored rectangle with the color name and RGB code

## 🚀 Installation 
```bash
git clone https://github.com/Harshi-3/Color-detection.git
cd Color-detection
pip install -r requirements.txt

