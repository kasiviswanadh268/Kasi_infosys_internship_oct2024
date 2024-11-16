# Kasi_infosys_internship_oct2024
AI enhanced engagement tracker for young learners

Welcome to the AI-Enhanced Engagement Tracker for Young Learners! This project was developed by Kasi Viswanadh during an internship at Infosys Springboard.

Overview 
The AI-Enhanced Engagement Tracker is designed to monitor and analyze young learners' engagement levels in real-time. Utilizing advanced AI techniques, this system provides educators and guardians with actionable insights, enabling a more effective and personalized learning experience.

The following are the stuff that we worked on during this tenure 

Developed Features:
1. Image Blurring Reduces noise and smoothens details in an image by averaging pixel values within a specified radius, enhancing visual clarity in high-noise scenarios.

Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/9e652a1e-5394-47c0-bcb2-ad2c9212fa05)

2. Rotation Rotates an image by a specified angle, useful for adjusting orientation or performing geometric transformations.
  
Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/37ffd01c-5193-488b-9b9f-630e98c29ddd)

3. Cropping Selects and isolates a specific region of interest from an image, allowing focus on a particular area without modifying the original image dimensions.

Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/c2634c1d-ddce-4d66-a7b7-90a8f542df71)

4. HSV Conversion Converts an image from RGB to HSV (Hue, Saturation, Value) color space, separating color information for more flexible color analysis and filtering.

Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/5146cb70-99d6-4e55-a01b-858d04e5d68a)

5. Contour Detection Identifies and highlights the boundaries of objects within an image, useful for shape analysis and object detection tasks.

Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/4dfb9cf4-64a6-45cf-9b20-eec2f713446d)

6. Dilation and Erosion Morphological transformations that expand (dilation) or shrink (erosion) object boundaries in an image, enhancing or reducing specific features for analysis.

Input 
![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)

Output 

![image](https://github.com/user-attachments/assets/25670cbe-1952-41ee-a6b6-fc6f0226dc7f)
![image](https://github.com/user-attachments/assets/a85ea836-02e3-4d3b-a6c3-2f7db3f9316f)

7.Histogram Equalization Adjusts the intensity distribution across an image to improve contrast, revealing finer details in images with poor lighting or low contrast. 

Input & Output

![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)
![image](https://github.com/user-attachments/assets/d5e6d6f8-8c99-40d1-aa79-8b6f923f4621)

8. Image Stacking Combines multiple images in either horizontal or vertical layouts, useful for comparison and visualization of variations between images.

Output 
![image](https://github.com/user-attachments/assets/bac094d6-780a-4b49-bf78-4fdb9075851e)

9. RGB to Grayscale Conversion Converts a colored image to grayscale by removing color information, simplifying analysis by reducing it to intensity variations.

Input & Output

![image](https://github.com/user-attachments/assets/ca12d135-5d94-4cf0-b0a8-7a4be76be915)
![image](https://github.com/user-attachments/assets/1923ccea-11ec-41af-b10c-dfbc3f9ec7a2)

10. Noise Addition Introduces random variations in pixel intensity, simulating real-world conditions for testing robustness in image processing algorithms.

Input 
![image](https://github.com/user-attachments/assets/1611b883-9a59-4464-9d5f-89e195c87831)

Output 

![image](https://github.com/user-attachments/assets/25670cbe-1952-41ee-a6b6-fc6f0226dc7f)
![image](https://github.com/user-attachments/assets/a85ea836-02e3-4d3b-a6c3-2f7db3f9316f)

11.HSV Conversion Converts an image from RGB to HSV (Hue, Saturation, Value) color space, separating color information for more flexible color analysis and filtering.

Input & Output

![image](https://github.com/user-attachments/assets/736ab232-7459-412d-a2a5-ea3003d8b982)
![image](https://github.com/user-attachments/assets/b41c7ac3-445d-4086-861b-90dedfad912d)

12.Edge Detection Highlights the edges within an image, emphasizing significant transitions between colors or intensities, often used for feature extraction. 

Input & Output

![image](https://github.com/user-attachments/assets/92b39d0d-c607-4c6e-9093-1e986ec02e58)
![image](https://github.com/user-attachments/assets/41a78fd6-d8a3-4e74-8fab-89edf55c112a)


Video Processing

Libraries/Frameworks Used:

OpenCV: 4.10.0.84

Developed Features:

1.Multi-video Processing

This function reads and displays images from a specified folder, printing the dimensions of each image.

![image](https://github.com/user-attachments/assets/1cd8c117-493e-4357-975a-36f54141db6b)

2. Video Stacking
This function reads and resizes two video files, concatenating them horizontally.

![image](https://github.com/user-attachments/assets/75e7e0f0-d273-4b85-a24a-faf9b7284e2d)

3.Frame Rate Adjustment
This function captures video from the webcam, displays it in real-time, and calculates the FPS.

![image](https://github.com/user-attachments/assets/99a7aac8-5076-4128-82df-972132de6f20)

4. Video Streaming
This function captures live video from the webcam and displays it in real-time.

![image](https://github.com/user-attachments/assets/d3b2655b-18ef-4f12-8231-50b7d1df493c)


Annotations


Libraries/Frameworks Used:

OpenCV: 4.10.0.84

LabelImg: 1.8.6

Developed Features:

1.Labeling
Used to draw bounding boxes on images based on annotations in the label files.

![image](https://github.com/user-attachments/assets/db57840e-a58b-4a70-b563-15fca9df334e)

2.Data Segregation
It organizes images and their label files into matched and unmatched directories.

![image](https://github.com/user-attachments/assets/16ac2649-b11e-478b-8153-0b12fa39f841)

3.Label Manipulation
It updates class numbers in label files for object detection tasks.

![image](https://github.com/user-attachments/assets/1901219b-c20e-4331-a566-e910112a2e3f)
