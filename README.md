# Cartoon Effect Using Machine Learning

This script uses machine learning and deep learning techniques to apply a cartoon effect to an image. It includes the following steps:

### Loading the Image
The script loads an image from a file using OpenCV.

### Creating an Edge Mask
An edge mask is created using adaptive thresholding to identify the edges in the image.

### Reducing the Color Palette
The script reduces the color palette of the image using K-Means clustering to create a more cartoon-like effect.

### Reducing Noise
The script applies a bilateral filter to reduce noise in the image.

### Combining the Edge Mask with the Quantized Image
The script combines the edge mask with the quantized image to create the final cartoonized image.

## Usage
To use this script, simply run it with the name of the image file you want to cartoonize as an argument. For example:
```bash
python cartoon.py cardiff_me.jpeg
```
## Output
The script will display the original image and the cartoonized image. The cartoonized image will be displayed with a title indicating that it is the cartoonified image.

## Requirements
- OpenCV
- NumPy
- Matplotlib

## License
This script is licensed under the MIT License.
