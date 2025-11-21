# SVM-Kernel-Methods-Machine-Learning-Project

This project demonstrates the implementation of Support Vector Machines (SVM) using different kernel functions, visualized through 2D scatter plots and interactive 3D charts (Plotly Express). The goal is to understand how various kernels (Linear, RBF, Polynomial) behave in feature space and how they influence classification performance.

📌 Project Overview

Support Vector Machines are powerful supervised learning algorithms used for classification. In this project:

A synthetic dataset is generated (classification type).

Data is visualized using both Matplotlib scatter plots and Plotly 3D charts.

SVM models are trained using:

Linear Kernel

RBF Kernel

Polynomial Kernel

Each model is evaluated using accuracy_score.

This project serves as a practical understanding of how kernels shape the decision boundaries.

🧪 Features Implemented

✔ Data generation for binary classification
✔ 2D scatter visualization using Matplotlib
✔ 3D visualization using Plotly Express
✔ Training SVM models with:

Linear Kernel

RBF Kernel

Polynomial Kernel
✔ Evaluation using accuracy_score
✔ Comparison of kernel performance
✔ Clean and understandable workflow

📊 Visualizations
Scatter Plot

Shows the distribution of generated feature points (two classes).

3D Plot (Plotly Express)

Interactive 3D chart that helps visualize separation in higher dimensions.

🧠 Modeling Approach
1. Linear Kernel

Good for linearly separable data.

2. RBF Kernel

Captures non-linear relationships by mapping data into infinite-dimensional space.

3. Polynomial Kernel

Allows curved decision boundaries; the degree parameter controls flexibility.

🔧 Libraries Used

numpy

pandas

matplotlib

plotly.express

sklearn

SVC

make_classification

train_test_split

accuracy_score
