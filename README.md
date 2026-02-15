# Lab 5 – Face Clustering using HSV Feature Space and K-Means

## Course
Machine Learning and Pattern Recognition

## Aim
The aim of this lab is to detect faces from an image, extract colour-based features using the HSV colour space, perform unsupervised clustering using K-Means, and classify a template face based on the learned clusters.

---

## Methodology

### Face Detection
- Haar Cascade Classifier was used to detect faces in the faculty image and the template image.
- Bounding boxes were drawn around the detected faces.

### Feature Extraction
- Each detected face was converted from BGR to HSV colour space.
- Mean Hue and Saturation values were computed for every face.
- These values were used as the feature vector for clustering.

### K-Means Clustering
- K-Means clustering was applied with K = 2.
- Each face was mapped into HSV feature space.
- Cluster centroids were computed and visualised.

### Template Face Classification
- The template image (Dr_Shashi_Tharoor.jpg) was processed in the same way:
  - Face detection
  - HSV conversion
  - Feature extraction
- The trained K-Means model was used to predict its cluster.
- The template face was plotted in the HSV feature space along with the faculty faces.

---

## Results and Observations

- Two distinct clusters were formed in the HSV feature space.
- The template face was successfully assigned to the nearest cluster based on its feature similarity.
- The template image had a lower saturation value compared to most faculty faces and appeared below the main cluster region in the feature space.
- The clustering demonstrates how colour-based features can group visually similar faces.

---

## Visual Outputs

### Faculty Face Detection
![Faculty Faces](Output%20images/faculty_faces_detected.jpg)

### Template Face Detection
![Template Face](Output%20images/template_face_detected.jpg)

### Clustering and Classification Results
All clustering visualisations, centroid plots, and template classification results are available in the Jupyter Notebook with outputs.

---

## Key Concepts Used

- HSV colour space
- Haar Cascade face detection
- Feature extraction
- K-Means clustering
- Centroid-based classification
- Distance-based learning

---

## Conclusion

This lab demonstrated unsupervised face clustering using low-dimensional colour features.  
K-Means successfully grouped the detected faces based on similarity in HSV space, and the template face was classified according to the nearest centroid. The experiment highlights how feature representation plays a crucial role in pattern recognition tasks.

---

## Tools and Libraries

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## Repository Structure

- Code/ → Jupyter notebook with outputs
- Output images/ → Saved face detection results
- Report.md → Written answers to the theory questions
- Lab 5_Spring 2026.pdf → Lab instructions
- README.md → Documentation

---

## How to Run

1. Clone the repository
2. Open the Jupyter notebook
3. Run all cells sequentially
4. Ensure the required images are present in the working directory

---

## Author
Vansh Jain

