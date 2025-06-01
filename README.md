# Non-Linearly Separable Data Classification with SVM

This repository contains an assignment project for the course Machine Learning - 1, focused on classifying non-linearly separable toy data using Support Vector Machines (SVM). The goal is to explore the limitations of linear SVMs and demonstrate how non-linear kernels (like RBF) can solve such problems.

## Contents

- Q1: Generate a non-linearly separable dataset and visualize it in 2D.
- Q2: Train a linear SVM, plot the decision boundary and support vectors, and evaluate its performance.
- Q3: Train a non-linear SVM with RBF kernel and visualize the decision surface in 3D.
- Q4: Plot the 2D decision boundary of the RBF SVM and support vectors.
- Q5: (Optional) Try alternative kernels and compare performance.

## Q1 – Toy Dataset Visualization

We generate a circular (non-linearly separable) dataset using `make_circles` from `sklearn.datasets`.


## Q2 – Linear SVM

We fit a linear SVM to the dataset and visualize the decision boundary and support vectors.

Evaluation:
- Misclassifications: Many samples misclassified.
- Margin: Computed using 2 / ||w||.
- Conclusion: Linear SVM fails due to the circular pattern of the data.


## Q3 – RBF Kernel SVM (3D Plot)

We fit a non-linear SVM with RBF kernel and visualize the decision function as a 3D surface.


## Q4 – RBF Kernel SVM (2D Boundary)

The decision boundary and margin are plotted in 2D. The RBF kernel successfully separates the classes.


## Technologies Used

- Python
- scikit-learn
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure

.
├── Q1_data_visualization.py  
├── Q2_linear_svm.py  
├── Q3_rbf_svm_3d.py  
├── Q4_rbf_svm_2d.py  
├── images/  
│   ├── q1_dataset.png  
│   ├── q2_linear_svm.png  
│   ├── q3_3d_surface.png  
│   └── q4_rbf_2d.png  
└── README.md

## Conclusion

This project demonstrates how non-linear SVMs with RBF kernels outperform linear SVMs in non-linearly separable data. The visualizations and decision boundaries make the performance difference clear.
