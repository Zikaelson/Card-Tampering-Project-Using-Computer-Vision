# Card-Tampering-Project-Using-Computer-Vision
This project aims to detect tampering in identification cards using computer vision techniques. It helps organizations verify the authenticity of ID cards provided by employees, customers, or other individuals. The project compares the original ID card with the user's uploaded ID card to identify any discrepancies and confirm its authenticity.

## Features:
Structural Similarity Index (SSIM): Utilizes SSIM to identify the precise locations of differences between the original and uploaded ID cards. A lower SSIM score indicates lower similarity.
Grayscale Conversion: Converts images to grayscale to simplify the analysis process, as grayscale images are easier to process than colored images.
Thresholding and Contour Detection: Applies adaptive thresholding to convert grayscale images into binary images, and then detects contours for shape analysis and recognition.
Visualization: Visualizes the differences and similarities between the original and uploaded ID cards by displaying images with contours and thresholds.

## Use Cases:
ID Verification: Organizations can use this project to verify the authenticity of various types of IDs, such as PAN cards, Aadhaar cards, voter IDs, and more.
Security: Enhances security measures by ensuring that provided identification is genuine and untampered.

## Technical Details:
Languages and Libraries: Python, OpenCV, scikit-image, PIL (Pillow), requests, imutils
Process: The project involves downloading images, converting them to grayscale, computing SSIM, applying thresholding, detecting contours, and visualizing the results.
