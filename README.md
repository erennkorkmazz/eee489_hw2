# eee489_hw2
README.md - Banknote Authentication with Decision Tree
 Project Structure
This project contains the implementation of a decision tree classifier to distinguish authentic and forged banknotes using the UCI Banknote Authentication dataset. It includes data preprocessing, exploratory analysis, model training, visualization, and evaluation.
Files Included
- `decision_tree.ipynb`  : Jupyter/Colab notebook with all code, visualizations, and outputs
- `ELE489_HW2_Full_Report.docx` : Written report with explanations, visual and analytical commentary
- `README.md`            : This documentation file
 How to Run
1. Open the `decision_tree.ipynb` notebook in Google Colab or Jupyter.
2. Run each cell from top to bottom:
   - Load and explore the dataset
   - Visualize features and compute statistics
   - Split the dataset into training and test sets
   - Train a decision tree model with `sklearn`
   - Evaluate performance and plot the confusion matrix
   - Visualize the decision tree and feature importances
 Dataset Info
Dataset: Banknote Authentication
Source: https://archive.ics.uci.edu/dataset/267/banknote+authentication
Features:
- Variance of Wavelet Transformed image
- Skewness of Wavelet Transformed image
- Kurtosis of Wavelet Transformed image
- Entropy of image
- Class (0 = Forged, 1 = Authentic)
 Libraries Used
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- scipy
 Notes
• The decision tree classifier achieved ~97% accuracy with interpretable rules.
• The model primarily relies on Variance and Skewness to classify samples.
• All visualizations are included in the notebook and the report.
