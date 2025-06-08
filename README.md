# k-Nearest Neighbors (kNN) Classification

This project explores the k-Nearest Neighbors (kNN) algorithm using both simulated and real-world datasets. It visualizes how the choice of `k` influences decision boundaries, evaluates model performance using cross-validation, and applies dimensionality reduction with PCA for interpretable visual insights.

---

## Dataset Sources

-  **Iris Dataset** – A classic dataset from `sklearn.datasets` with 150 samples and 4 features (sepal/petal length/width)

---

##  Techniques Used

- Distance-based classification with **kNN**
- **Hyperparameter tuning** (`n_neighbors`)
- **Cross-validation** to select the optimal `k`
- **Confusion matrix** and accuracy evaluation
- **PCA (Principal Component Analysis)** to visualize feature separability in 2D and 3D

---

## Project Structure

### Part 1: Simulated kNN Visualization
- Visualizes decision boundaries on a synthetic 2D dataset
- Demonstrates overfitting vs. underfitting at different `k`

### Part 2: Tuning `k` with Cross-Validation
- Evaluates test accuracy across different values of `k`
- Selects the best-performing `k` using cross-validation

### Part 3: kNN on Iris Dataset
- Applies kNN to classify Iris flowers using all 4 features
- Evaluates accuracy on test set

### Part 4: PCA (2D & 3D) Visualization
- Reduces Iris feature space to 2 and 3 principal components
- Plots predicted vs. actual class labels in 2D and 3D

---

##  Key Results

- Achieved strong accuracy on the Iris dataset with `k=13`
- PCA visualizations clearly separated the Setosa class
- Identified slight class overlap between Versicolor and Virginica in both 2D and 3D

---

##  Technologies

- Python (Jupyter Notebook)
- `scikit-learn`
- `matplotlib`, `seaborn`
- `numpy`, `pandas`

---

