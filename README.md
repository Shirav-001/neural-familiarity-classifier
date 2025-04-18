# Neural Familiarity Classifier

**Author:** Shiraf Moussa
**Matriculation No.:** 1011541

## Project Overview
We build a binary classifier using scikit‑learn to predict whether a stimulus is familiar or novel
based on multi‑neuron spike‑train recordings.

## Data
- **X:** 800 trials × N_neurons × T_timesteps spike trains  
- **y:** Binary labels (familiar = 1, unfamiliar = 0)

## Methodology
1. Preprocessing: bin spikes into firing rates  
2. Feature extraction: per‑neuron rate vectors, optional PCA  
3. Model selection: Logistic Regression (+ hyperparameter tuning)  
4. Evaluation: 5‑fold CV, ROC AUC, confusion matrix  

## Usage
```bash
pip install -r requirements.txt
jupyter notebook

