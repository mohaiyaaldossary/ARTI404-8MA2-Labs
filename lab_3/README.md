# Image Processing Lab – Color Spaces and Transformations

## 📖 About This Lab
This lab focuses on color space conversion, geometric transformations, and intensity transformations using OpenCV and NumPy.

The image used in this lab is `cat.jpg`.

---

## 🖼 Part 1: Image Color Processing

### Tasks Performed:
- Read a color image using OpenCV
- Converted BGR to RGB for correct display
- Converted image to Grayscale
- Saved grayscale image as `output.jpg`
- Converted image to YUV color space
- Displayed Y, U, and V channels separately
- Printed number of available OpenCV color conversion flags

### Concepts Learned:
- Image shape (Height, Width, Channels)
- Color space conversion
- Channel separation

---

## 🔄 Task 1: Geometric Transformations

### 1️⃣ Resize
- Increased image size 2x using linear interpolation.

### 2️⃣ Rotation
- Rotated image by 120 degrees using rotation matrix.

### 3️⃣ Shear Transformation
- Applied affine shear transformation using a shear matrix.

---

## 🌗 Task 2: Intensity Transformations

### 1️⃣ Negative Transformation
- Created image negative using:
  255 - image

### 2️⃣ Log Transformation
- Enhanced dark regions using logarithmic scaling.

### 3️⃣ Power-Law (Gamma) Transformation
- Applied gamma correction with γ = 0.4

Saved outputs:
- negative.jpg
- log.jpg
- gamma.jpg

---

## 🛠 Tools Used
- Python
- NumPy
- OpenCV (cv2)
- Matplotlib

---

## 🎯 What I Learned
- How images are stored as NumPy arrays
- Working with color spaces (BGR, RGB, Grayscale, YUV)
- Applying geometric transformations (resize, rotate, shear)
- Performing intensity transformations (Negative, Log, Gamma)
- Saving processed images
