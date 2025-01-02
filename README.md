# Data Analysis to Predict Anxiety Disorders in Childern

## Project description
This project anayzes behavioral, psychophysiological, and demographic data collected from preschool children (3-5 years old) to predict the risk of anxiety disorders, including Separation Anxiety (SAD) and Gnerealized Anziety (GAD). Is uses machine learning algorithms, such as Random Forest, to build robust predictive models.
Results include assessment metrics, ROC curves, confusion matrices, and feature importance. Results are exported from the research paper "Quantifying Risk for Anxiety Disorders in Preschool Children: A Machine Learning Approach".

## Main Features
- **Data processing**: Null value imputation, feature scaling.
- **Hyperparameter optimization**: Grid search to improve model performance.
- **Model evaluation**: Metric such as Accuracy, Precision, Recall, F1 Score, and AUC.
- **Visualizations**: ROC curves and confusion matrices.

## Requirements
### Required Libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `openpyxl`

## Instalation
Run the following command to install the dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn openpyxl
```

## Project Structure
- `Training_Data.xlsx`: Input data file.
- `anxiety_ml_analysis.py`: Main code for analysis.
- `Resultados_Modelo_SAD_GAD.xlsx`: Generated results (Accuracy, Precision, Recall, F1 Score, and AUC for SAD and GAD)

## Code execution

1. Make sure that the `Training_Data.xlsx` file is in the same folder as the script.
2. Execute the code in a Python environment:
   ```bash
   python anxiety_ml_analysis.py
   ```
3. Check results:
   - Evaluation mectris and visualizations are printed and displayed during execution.
   - The final results are stored in `Resultados_Modelo_SAD_GAD.xlsx`.

## Generated results
1. ROC curves: Visualizations to evaluate the classification ability of models for SAD and GAD.
2. Confusion Matrices: Tables to analyze false positives, false negatives, true positives and tru negatives.
3. Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- AUC (Area Under the Cure)
