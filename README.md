# Customer Segmentation with Dimensionality Reduction

This Python project demonstrates customer segmentation using K-means clustering and dimensionality reduction techniques such as PCA (Principal Component Analysis) and t-SNE (t-distributed Stochastic Neighbor Embedding). It is designed to help businesses identify distinct customer segments based on their purchasing behavior and other features.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Customer segmentation is a crucial task for businesses, as it allows for targeted marketing strategies and personalized recommendations. This project aims to provide a practical example of how to perform customer segmentation using K-means clustering and dimensionality reduction with PCA and t-SNE.

## Features

- Data loading from CSV or Excel files.
- Removal of duplicate rows.
- Removal of specified columns from the dataset.
- Label encoding or one-hot encoding of categorical columns.
- Handling of missing values, including the option to remove rows with NaN values.
- Dimensionality reduction using PCA or t-SNE.
- Determining the optimal number of clusters using the elbow method (for PCA and t-SNE).
- K-means clustering with cluster assignment.
- Visualization of clusters and cluster centers.
- Interactive cluster selection based on dimensionality reduction technique.
- Silhouette score evaluation of clustering quality.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages (dependencies are listed in the code file)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/OmarAdel777/customer-segmentation.git
   cd customer-segmentation


 
2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Python script `customer_segmentation.py` in your preferred development environment.

2. Follow the on-screen instructions to load your data, preprocess it, choose encoding options, handle missing values, and perform customer segmentation.

3. After completing the process, the script will provide cluster profiles, visualizations, and evaluation metrics.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

- Fork the repository on GitHub.
- Create a new branch for your feature or bug fix.
- Make your changes and test thoroughly.
- Create a pull request to merge your changes into the main branch.

