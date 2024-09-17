# Bloodcell_classification
Bloodcell_classification from scratch and sklearn

In this project, the goal is to automate the classification of blood cell types for large-scale analysis of experiments in leukemia research. The classification task is essential for understanding how different compounds influence the distribution of blood cell types. Automating this process eliminates the need for manual effort, allowing for the analysis of thousands of experiments involving millions of cells.

Preprocessing has already been completed, where blood samples were stained using Giemsa, captured using automated microscopes, and then segmented into specific cell regions. The segmentation pipeline is based on Cellpose, and the features of the cells were extracted using FIJI/ImageJ, a popular image analysis tool. The dataset includes features such as size, shape, and intensity, along with two key datasets: bloodcells_train.csv and bloodcells_test.csv.

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/2ead768d-861d-4c9a-83e4-baec9d5f67d2" alt="image" width="1000"/>
</div>


<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/bb9906dd-e9e2-4b4b-96da-6d5c4745587d" alt="image" width="1000"/>
</div>




It includes training and evaluating different machine learning models for predicting blood cell types:

* **Comparison of models:** Including logistic regression, multi-layer perceptron (MLP), and other classifiers, with a focus on optimizing for the F1 score.
* **Grid search for hyperparameter tuning:** Experimenting with batch sizes, learning rates, and network architectures.
* **Confusion matrices and metrics:** Visualizing the confusion matrix and calculating key metrics like accuracy and F1 score to evaluate model performance.



<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/b0068b35-9cf0-4f8a-bbf3-e4564bc2a4e4" alt="image" width="400"/>
</div>
