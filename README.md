# Code results for explainable AI paper
An **Open Source**  code released to increase reproducibility in academic and professional research.

## Paper info
- **Title**:
- **Access Link**:
- **DOI**:
- **Journal**:
- **Journal Impact Factor**:

## Authors info
- Kaike Wesley Reis (**corresponding author**): [LinkedIn](https://www.linkedin.com/in/kaike-wesley-reis/) and [Lattes](http://lattes.cnpq.br/0566221555180240)
- Karla Patricia Oliveira-Esquerre: [LinkedIn](https://www.linkedin.com/in/karla-esquerre-5a1b2234/) and [Lattes](http://lattes.cnpq.br/1956096628005272)

## Overall AI framework
![AI pipeline](https://user-images.githubusercontent.com/32513366/89131523-c9692f80-d4e3-11ea-8738-9405275f972e.png)

**Disclaimer**: The supplementary material provided in this repository contains extra analysis and discussions compared to the paper discussion. This decision was made to make the results presented more focused and objective for the paper.

## Best selected model info
- **AI mmodel**: Random Forest
- **Overall parameters (including hyperparameters)**:
 
  ```
  {'bootstrap': True,
  'ccp_alpha': 0.0,
  'class_weight': 'balanced_subsample',
  'criterion': 'gini',
  'max_depth': 21,
  'max_features': 'sqrt',
  'max_leaf_nodes': None,
  'max_samples': None,
  'min_impurity_decrease': 0.0,
  'min_impurity_split': None,
  'min_samples_leaf': 1,
  'min_samples_split': 2,
  'min_weight_fraction_leaf': 0.0,
  'n_estimators': 1000,
  'n_jobs': None,
  'oob_score': False,
  'random_state': 1206,
  'verbose': 0,
  'warm_start': True}
  ```

## Repository info
- The `.ipynb` was used to developed the source material related to this paper.
- The numbers at the beginning of each notebook represent the pipeline order:
  - `0` and `1` for Pre-processing
  - `2` for Model development
  - `3` for Results evaluation (model selection)
  - `4` for Qualitative analysis
- The original dataset can be found [here](https://www.kaggle.com/einsteindata4u/covid19) at Kaggle's platform.

## Requirements
The `requirements.txt` was generated outside a virtual environment and then presents all packages installed on the machine without exception. Given this fact, I separated the main packages, followed by their versions, used for this paper:

Package       | Version
------------ | -------------
numpy        | 1.18.1
pandas       | 1.0.5
missingno    | 0.4.2
matplotlib   | 3.1.3
seaborn      | 0.10.0
scikit-learn | 0.23.1
skopt        | 0.8.dev0
xgboost      | 1.1.1
scipy        | 1.4.1
joblib       | 0.14.1
shap         | 0.38.0
umap         | 0.4.6
imbalanced-learn  | 0.7.0
