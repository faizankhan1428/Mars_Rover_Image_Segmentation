# Mars Rover Image Segmentation

This project uses classical computer vision techniques to segment and classify terrain in real Mars images captured by NASA’s Curiosity rover.

## 🔍 Overview
Using a dataset from Kaggle, we processed raw grayscale images taken by the rover’s front and rear hazard cameras (FHAZ, RHAZ) and navigational cameras (NAVCAM). The goal was to segment terrain regions and classify them as **rocky** or **smooth** using feature-based machine learning.

## 📁 Dataset
**Dataset Name:** Mars Curiosity Image Dataset  
**Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/sidhus/crater-mars-curiosity-dataset)

## 📌 Project Steps

### Step 1: Load and Preview the Dataset
Images were loaded from the dataset and resized for analysis.

### Step 2: Image Segmentation
We applied grayscale thresholding and morphological operations to extract terrain regions.

### Step 3: Edge Detection & Contour Extraction
Canny edge detection and contour analysis were used to detect shapes and terrain boundaries.

### Step 4: Terrain Classification
- **4.1 Feature Extraction:** Texture and intensity features were extracted using `skimage`.
- **4.2 Classification:** Trained a Random Forest Classifier to categorize patches as rocky or smooth.

### Step 5: Visualize Classified Terrain
Classified image patches were displayed with labels overlaid.

### Step 6: Terrain Statistics
Computed the percentage of rocky vs smooth patches across each image.

### Step 7: PCA for Feature Space Visualization
Principal Component Analysis (PCA) was used to visualize feature distribution in 2D space.

### Step 8: Save and Share
Notebook was saved and exported for sharing. Model export and future inference were also considered.

## 📌 Results
- The classifier showed effective performance on unseen image patches.
- Smooth vs Rocky terrain segmentation worked well under varying light and camera angles.

## 📎 Notebook
Access the full notebook on Kaggle:  
**[Mars Rover Image Segmentation](https://www.kaggle.com/code/faizankhandeshmukh/mars-rover-image-segmentation)**

## 🧠 Future Work
- Integrate deep learning models (e.g., U-Net) for advanced segmentation.
- Apply transfer learning on Mars terrain datasets with RGB imaging.
- Extend analysis for obstacle detection in autonomous navigation.

---

**This project demonstrates how classical vision techniques can still play a vital role in real-world space exploration problems.**
