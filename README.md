# Data Challenge ENT

This repository contains various components and resources for the ENT data challenge. Below is an overview of the structure, functionality, and purpose of each file and folder within the project.

---

## **Project Structure**

### **Folders**

#### `Trial`
- Contains trial runs and experiments conducted during the development process.
- Includes some files with identified errors and operations that initially had data leakage issues, which were subsequently corrected.

#### `bestmodels`
- Stores the best-performing models derived from the grid search process in `abstract_models_2.ipynb`.
- **Note:** The best model for the Random Forest algorithm was not included due to its large size.

#### `Data_metrics`
- Contains datasets extracted after the preprocessing phase.
- These datasets were utilized across various notebooks for further analysis and modeling.

---

### **Notebooks**

#### `main.ipynb`
- The primary notebook that provides a complete pipeline from start to finish.
- Includes comprehensive comments explaining each step in detail, making it easy to follow and understand.

#### `abstract_models_2.ipynb`
- Focuses on the analysis of basic machine learning models.
- Implements grid search for hyperparameter tuning to identify the best-performing configurations for various models.

#### `data_splitting_1.ipynb`
- Details an initial pipeline for splitting the data into training and testing sets.
- Evaluates this data splitting approach using some models to ensure its effectiveness.

#### `GraphNNN.ipynb`
- Includes the implementation of graph neural networks trained on graph-structured data combined with additional features.

#### `topic_visualisation.ipynb`
- Provides a general analysis of the dataset derived from the papers.
- Contains insightful visualizations that reveal patterns and trends within the data.

---

### **Key Highlights**
- **Error Handling:** Early experiments encountered errors and data leakage, which were meticulously resolved to ensure robust and reliable results.
- **Comprehensive Pipeline:** The `main.ipynb` serves as the backbone of the project, integrating preprocessing, modeling, and evaluation into a seamless workflow.
- **Model Optimization:** Detailed hyperparameter tuning was performed for basic machine learning models in `abstract_models_2.ipynb`, ensuring optimal performance.
- **Graph Analysis:** The `GraphNNN.ipynb` explores advanced techniques using graph neural networks to leverage the graph-like nature of the data.
- **Visualization:** Rich visualizations in `topic_visualisation.ipynb` provide a deeper understanding of the dataset, aiding in decision-making and analysis.

---