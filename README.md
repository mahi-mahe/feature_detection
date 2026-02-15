# feature_detection
Hi, I am Mahi Maheshwari, a PGDM student in AI & Data Science.  
This project is my implementation of the Harris Corner Detector built from scratch to understand how corner detection works internally.

---

## What this project does
The project does following tasks:
- Computes image gradients using Sobel operators  
- Forms the structure tensor  
- Calculates the Harris response  
- Applies thresholding and non-maximum suppression  
- Returns corner locations and visualizes them on the image  

---

## My reason to build is because instead of only calling OpenCV functions, I wanted to learn what happens inside the algorithm. Writing it myself helped me understand how gradients, intensity variation, and neighborhood operations decide whether a pixel is a corner.

---

## Following are the steps to be followed to run the code:

Step1. Provide an input image.
Step2. Now run the notebook or script.
Step3. The output image will be generated that shows detected corners.

## Tech stack

- Python  
- NumPy  
- OpenCV  
- SciPy  

## Output

The harris and fast algorithm marks corners on chessboard and boxes images as per the industry requirements like amzon warehouse or manufacturing. Here I used a chessboard image with 64 squares for showcasing the output. At the end there is a time(log scale) comparison between fast and opencv.

---

## Learning Outcome

This exercise helped me work with raw images and implement feature detectors that can be employed for industrial applications and CV pipelines. I also think, these code snippets can be deployed during inventory manaagement, robotics, manufacturing, etc. 
