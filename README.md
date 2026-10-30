# Image Processing with Python – Assignment 2

## About the Project

This repository contains my **Image Processing Practical Assignment 2**, completed as part of the PGDM in Big Data Analytics.

The assignment focuses on understanding the fundamentals of digital image processing using Python. It includes practical implementations of image reading, displaying, resizing, cropping, rotating, flipping, colour space conversion, and image quality evaluation.

All practical exercises are implemented using Python in Jupyter Notebook.

## Practical Experiments

This assignment covers the following ten practical exercises:

### 1. Read and Display an Image
- Read an image using OpenCV.
- Display the original image in a separate window.

### 2. Print Image Dimensions and Data Type
- Extract image height, width, and number of colour channels.
- Identify the image data type using NumPy.

### 3. Convert a Colour Image to Grayscale
- Convert a colour image into grayscale using OpenCV.
- Save the processed image as `output_gray.jpg`.

### 4. Open an Image Using Pillow
- Load an image using the Pillow library.
- Display the image directly inside the Jupyter Notebook.

### 5. Resize an Image to 50%
- Resize an image to half of its original width and height.
- Understand image resizing using OpenCV.

### 6. Crop the Central 200 × 200 Pixel Area
- Extract the central 200 × 200 pixel region of an image.
- Display the cropped image using Matplotlib.

### 7. Rotate an Image 90 Degrees Clockwise
- Rotate an image by 90 degrees clockwise.
- Understand image rotation using OpenCV.

### 8. Flip an Image Horizontally
- Flip an image from left to right.
- Display the horizontally flipped result.

### 9. Convert an Image to HSV
- Convert an image from RGB to HSV colour space.
- Display the Hue, Saturation, and Value channels separately.

### 10. Calculate Mean Squared Error (MSE)
- Calculate the Mean Squared Error between two grayscale images.
- Understand how MSE measures the difference between images.

## Technologies and Libraries Used

- **Python** – Core programming language.
- **OpenCV (cv2)** – Image reading, processing, resizing, cropping, rotation, flipping, and colour space conversion.
- **NumPy** – Numerical computations, image arrays, data types, and MSE calculation.
- **Matplotlib** – Image visualisation and displaying individual colour channels.
- **Pillow (PIL)** – Opening and displaying image files.
- **IPython.display** – Displaying images directly inside Jupyter Notebook.
- **OS** – File and directory path handling.

## Key Concepts and Techniques

- Image Reading and Displaying
- Image Dimensions and Data Types
- RGB to Grayscale Conversion
- Image Resizing and Cropping
- Image Rotation and Flipping
- RGB to HSV Colour Space Conversion
- Hue, Saturation, and Value Channels
- Mean Squared Error (MSE)
- Basic Image Manipulation using OpenCV

## Project Structure

```text
Image-Processing-with-Python/
│
├── Swasti_BDA_ASS_2.ipynb
├── car.jpg
├── flower.jpg
├── img2.jpg
├── output_gray.jpg
├── scene.jpeg
└── sunset.jpg
```

## Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/Swasti0426/Image-Processing-with-Python.git
```

### 2. Navigate to the Project Folder

```bash
cd Image-Processing-with-Python
```

### 3. Install Required Libraries

```bash
pip install opencv-python numpy matplotlib pillow ipython
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open `Swasti_BDA_ASS_2.ipynb` and execute the cells sequentially.

**Note:** Keep all supporting image files in the same folder as the notebook. Update any local file paths in the notebook if required.

## Key Learning Outcomes

Through this assignment, I gained practical experience in:

- Reading and displaying digital images using Python.
- Understanding image dimensions, channels, and data types.
- Performing basic image transformations.
- Working with different colour spaces such as RGB, Grayscale, and HSV.
- Using OpenCV and Pillow for image manipulation.
- Visualising images and colour channels using Matplotlib.
- Evaluating image differences using Mean Squared Error.

## Author

**Swasti Agrawal**

PGDM – Big Data Analytics (BDA)

---

*This repository is part of my academic practical work in Image Processing using Python.*
