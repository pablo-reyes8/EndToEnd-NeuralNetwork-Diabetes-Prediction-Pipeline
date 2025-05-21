## Project Overview

End-to-end pipeline for **diabetes prediction** using **Neural Networks** in both **Keras** and **PyTorch**. This project covers:

- **Exploratory Data Analysis** & Feature Engineering  
- **Advanced Preprocessing**: SMOTE for class balance, PCA for dimensionality reduction, polynomial feature expansion  
- **Model Definitions**: Separate implementations in Keras and PyTorch  
- **Hyperparameter Tuning**: Automated search with Keras Tuner  
- **Training & Evaluation**: Code to train, validate, and compare models across frameworks  

## Features

- Streamlined data ingestion and preprocessing  
- Modular model architectures you can extend  
- Automated Keras hyperparameter sweeps  
- Clear training/validation routines with accuracy and loss reporting  

## Data

- `pima-indians-diabetes.csv` Contains the original database without any preprocessing.
- `Diabetes_1.csv`  Contains the base that is reached after feature engineering and data imputation

## Important Dependencies

```bash
pip install pandas numpy scipy matplotlib tensorflow keras_tuner pytorch sklearn imblearn   
```

## How to Use

1. Open `DIabetes Neural Network.ipynb` in Jupyter Notebook or JupyterLab.  
2. Run all cells in order to reproduce the full pipeline.  
3. Modify the Parameters cell to experiment with both your neural network architecture (e.g. number of layers, units per layer, activation functions, dropout rates) and your preprocessing pipeline (e.g. SMOTE ratio, number of PCA components, LDA dimensions, polynomial feature degree, etc.).  

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests at  
https://github.com/pablo-reyes8

## License

This project is licensed under the Apache License 2.0.  
