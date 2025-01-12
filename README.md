# Face Recognition with PCA

This project implements a face recognition system based on the Eigenfaces method, which utilizes [Principal Component Analysis (PCA)](https://en.wikipedia.org/wiki/Principal_component_analysis) for feature extraction and a nearest-neighbor classifier for face identification. The project works with the [Yale B](https://cvc.cs.yale.edu/cvc/projects/yalefacesB/yalefacesB.html) face dataset, consisting of images captured under varying lighting conditions.

## **Features**
- Face Recognition System: We implement the Eigenfaces approach, combining PCA for dimensionality reduction with a nearest-neighbor classifier to efficiently identify faces.
- Performance Evaluation: We analyze reconstruction errors and classification accuracy across different subsets of the dataset, offering insights into the impact of varying the number of principal components.
