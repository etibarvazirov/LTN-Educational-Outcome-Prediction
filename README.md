
# Combining Logic Rules and Neural Models for Educational Outcome Prediction with LTN

This repository contains the implementation of a hybrid model that combines symbolic logic rules with neural networks using Logic Tensor Networks (LTN) to predict whether students will pass based on various academic and behavioral features.

## Project Overview

This project demonstrates how to incorporate domain knowledge through logical constraints into a neural model using the LTN framework. The model is evaluated using a student performance dataset.

## Repository Structure

```
LTN-Educational-Outcome-Prediction/
│
├── data/
│   ├── student-mat.csv            # Original dataset
│   └── ltn_student_data.csv       # Preprocessed/modified version 
│
├── figures/
│   ├── Confusion Matrix.png
│   ├── Distribution of Prediction Probabilities on Test Set.png
│   ├── Test Accuracy Comparison(Standard NN vs LTN).png
│   ├── Training Progress_ Sat Level vs. BCE Loss.png
│   └── Weighted Contributions to SAT Level.png
│
├── Combining_Logic_Rules_and_Neural_Models_for_Educational_Outcome_Prediction_with_LTN(E_VAZIROV).ipynb
├── README.md
├── requirements.txt

```

## Notebook

- `Combining_Logic_Rules_and_Neural_Models_for_Educational_Outcome_Prediction_with_LTN(E_VAZIROV).ipynb`: Main Colab notebook implementing LTN-based and standard neural models, with logical rules and evaluations.

## Dataset

- `student-mat.csv`: Original dataset from the UCI Machine Learning Repository containing student background and academic performance data.
- The dataset was processed to create a binary classification target `Pass`, used for training the model.

## Running the Notebook

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload `student-mat.csv` to your Colab runtime or ensure it's in the same folder if running locally.
3. Run all cells to:
   - Preprocess data
   - Define logic-based rules
   - Train LTN and standard models
   - Generate visualizations and evaluation metrics

## Visualizations

The notebook includes the following visualizations:
- Weighted satisfaction contributions of logic rules
- Training progress of SAT level vs. BCE loss
- Accuracy comparison of models
- Confusion matrix
- Prediction probability distribution

## Dependencies

Make sure to install the required libraries:

```bash
pip install LTNtorch pandas scikit-learn matplotlib seaborn torch
```

## Author

Etibar Vazirov

PhD Student, @DAUIN, Politecnico di Torino


## Citation

If you use or reference this project, please cite:

    Etibar Vazirov (2025). Combining Logic Rules and Neural Models for Educational Outcome Prediction with LTN


