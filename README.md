PCA for Facial Recognition and Generation using CelebA Dataset

Overview

This project leverages Principal Component Analysis (PCA) to explore facial recognition and generation using the CelebFaces Attributes (CelebA) dataset. It involves data preprocessing, dimensionality reduction, face reconstruction, and the generation of random faces through PCA.
Tasks

1. Data Preparation
Load the CelebA facial images.
Resize all images to a consistent size and convert them to grayscale.
Transform each image into a 1D vector representing pixel intensities.
2. PCA Analysis
Arrange the image vectors into a matrix where each row represents a face.
Center the data by subtracting the average face vector.
Perform PCA to identify the principal components that capture the most significant variance in facial features.
3. Face Reconstruction
Reconstruct faces using a selected number of principal components to balance detail and accuracy.
Compare the original and reconstructed faces to evaluate reconstruction quality as the number of components changes.
4. Project Your Face
Identify the closest celebrity face to your own in the PCA space.
5. Random Face Generation
Generate new face images by manipulating PCA components and visualizing the results.
6. Evaluation
Measure reconstruction accuracy using metrics like mean squared error (MSE).
Evaluate the realism of generated faces.
Installation

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/pca-face-recognition.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage

Prepare the CelebA dataset by downloading it from here.
Run the main Python file to perform PCA analysis and visualize results:
bash
Copy code
python pca_face_recognition.py
Use the generated visualizations to compare original and reconstructed faces or view the generated random faces.
Results

Visualize both the original and PCA-reconstructed faces.
Explore random face generation by manipulating principal components.
Identify the closest celebrity in the dataset based on PCA representation.
Requirements

Python 3.x
NumPy
pandas
scikit-learn
matplotlib
OpenCV (optional, for image processing)
License

This project is licensed under the MIT License.
Acknowledgments

Dataset: CelebA
PCA implementation: scikit-learn
