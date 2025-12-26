# Exploring the Yeast Gene-Expression Landscape

## 📖 Project Overview

This project explores the landscape of gene expression data from the Yeast dataset, focusing on the challenges of high-dimensional, multi-label biological data. The analysis leverages advanced manifold learning techniques, **t-SNE** and **Isomap** to visualize and interpret the structure, imperfections, and class overlaps within the data. The notebook demonstrates how these dimensionality reduction methods reveal both local and global patterns, providing insights into noisy labels, outliers, and the intrinsic complexity of the classification problem.

## 📁 Repository Structure

```
ManifoldLearning/
│
├── main.ipynb
├── yeast_dataset/
│   └── yeast.csv
└── README.md
```


- **main.ipynb**: The main Jupyter notebook containing all code, analysis, visualizations, and conclusions.
- **yeast_dataset/**: Directory containing the dataset used for analysis.
    - **yeast.csv**: The yeast gene expression dataset.
- **README.md**: Project documentation and instructions.

## Dependencies

- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run This Project
1. **Clone the Repository**
    ```bash
    git clone https://github.com/Charukhesh/ManifoldLearning.git
    cd ManifoldLearning
    ```

2. **Dataset**

    Ensure the yeast.csv file is present in the yeast_dataset/ folder.

3. **Open and Run the Notebook**
    - Open `main.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [VS Code](https://code.visualstudio.com/).
    - Run all cells sequentially to reproduce the analysis and results.
