

#### Project Overview:
This project implements a **decision tree classifier** to predict neutron interaction events as part of the research at the Virginia State University Nuclear Science Lab, specifically for the **Modular Neutron Array (MoNA)** project. The focus is on classifying neutron trajectories using machine learning techniques based on measurements from scintillator detector arrays.

The decision tree model was developed to analyze data collected from **MoNA** and **LISA** detectors. This model helps in automating the classification of neutron interaction events by learning complex decision boundaries from the data.

#### Files:
- `decisiontree.ipynb`: Contains the decision tree implementation using **Scikit-learn**. This notebook includes data preprocessing, model training, hyperparameter tuning, and performance evaluation steps.

#### How to Run:
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   where `requirements.txt` includes:
   ```
   scikit-learn
   pandas
   numpy
   matplotlib
   ```
2. Open the notebook:
   ```bash
   jupyter notebook decisiontree.ipynb
   ```
3. Follow the steps outlined in the notebook to load the dataset, train the model, and visualize its performance using metrics such as **accuracy**, **precision**, and **recall**.

#### Key Features:
- Implementation of a decision tree model to classify neutron interactions.
- Feature engineering and data preprocessing, including normalization and handling missing values.
- Hyperparameter tuning using **grid search** and cross-validation.
- Visualization of the decision boundaries and evaluation of model performance.

#### Contributors:
- **Raven Mott**: Developed the machine learning model for neutron interaction classification, including data preprocessing and decision tree implementation. Contributed to integrating the model into the **MoNA** analysis software pipeline.
- **Dr Thomas Redpath**:PI
- **Facility for Rare Isotope Beams (FRIB)**

