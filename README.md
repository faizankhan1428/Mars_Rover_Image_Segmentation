Mars Rover Image Segmentation
This project explores image segmentation and terrain classification using real Mars images from NASA's Curiosity Rover. We used classical computer vision techniques to analyze images, identify features, and classify terrain into rocky vs smooth areas.

We also applied PCA to visualize the extracted features in lower dimensions.

Project Notebook:
Kaggle Notebook Link: https://www.kaggle.com/code/faizankhandeshmukh/mars-rover-image-segmentation

Dataset
Name: Mars Curiosity Image Dataset
Source: https://www.kaggle.com/datasets/lnicole/mars-curiosity-dataset
Description: A multi-camera image dataset from NASA’s Curiosity rover, including NAVCAM, FHAZ, and RHAZ images. We used a subset of front and rear hazcam grayscale images.

Steps Overview
Step 1: Load and Display Images

Loaded and displayed sample grayscale images from the rover's navigation cameras.

Step 2: Image Segmentation

Applied grayscale thresholding to segment key features.

Step 3: Edge Detection and Contours

Used Canny edge detection and contour approximation to identify terrain boundaries.

Step 4: Feature Extraction and Classification

Extracted small image patches, computed texture features using Local Binary Pattern (LBP), and trained a classifier to predict terrain type.

Step 5: Terrain Classification Visualization

Predicted and visualized rocky vs smooth regions using color masks over images.

Step 6: Terrain Ratio Calculation

Calculated and displayed the percentage of rocky vs smooth terrain.

Step 7: Feature Space Visualization

Used PCA to reduce LBP feature space to 2D and visualized it.

Step 8: Save and Share

Prepared the notebook for sharing and saved the trained model (optional).

Outcome
Successfully segmented Mars terrain into rocky and smooth regions.

Visualized terrain statistics and features.

Demonstrated practical use of edge detection, feature extraction, classification, and dimensionality reduction.

Future Work
Use deep learning (like U-Net or ResNet) for improved segmentation.

Train on more labeled data from other Mars missions.

Extend classification into more terrain types like sandy, hilly, or cratered.

Apply object detection to identify rover parts, shadows, or obstacles.