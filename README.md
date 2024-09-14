# Curvetopia

Curvetopia is a project developed as part of the Adobe Gensolve hackathon. This project focuses on shape regularization, symmetry detection, and curve completion using various machine learning and data visualization techniques.

## Team Members
- [Simarjeet Singh Mehra](https://github.com/ssmehra7)
- [Ankit Raj](https://github.com/turbulent7)

## Project Overview
Curvetopia consists of three main approaches, each implemented in separate Jupyter notebooks (`.ipynb`). Each notebook addresses a unique problem related to shape detection, symmetry detection, and curve completion.



### 1. Occulsion_Symmetry_detection_approach_1_line of symmetry.ipynb
This notebook focuses on symmetry detection within regular shapes. It uses the `hexplot` function to draw lines of symmetry, saving the output in SVG format for high-quality visual representation. The method is particularly effective for identifying symmetry in hexagonal shapes.

### 2.Regularization_and_Symmetry_detection_for_isolated_and_frag.ipynb
This notebook is the most comprehensive of the three, addressing multiple tasks:
- **Regularization of `frag0.csv` Dataset:** It regularizes the shapes within the dataset, improving their structure for further analysis.
- **Curve Completion:** It applies techniques like Bezier curves to complete the shapes, ensuring smooth and aesthetically pleasing curves.
- **Symmetry Detection:** The notebook introduces a new approach to detecting both horizontal and vertical lines of symmetry within the `frag0.csv` dataset.
- **Visualization:** It visualizes the regularized and completed shapes, showcasing the improvements made through the regularization and curve completion processes.

## Getting Started
To run these notebooks, you will need:
- Python 3.x
- Jupyter Notebook
- Required libraries: numpy, pandas, matplotlib, and any other specific libraries mentioned in the notebooks.

Clone the repository and open each `.ipynb` file in Jupyter Notebook to explore the different approaches and outputs.

## Conclusion
Curvetopia presents innovative solutions to shape regularization, symmetry detection, and curve completion. Each notebook in the project contributes to a deeper understanding of these complex tasks, with practical applications in design, pattern recognition, and data visualization.

We hope this project provides valuable insights and inspiration for future developments in shape analysis and symmetry detection.

