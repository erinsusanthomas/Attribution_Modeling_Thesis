# Attribution Modeling Thesis Repo (Erin Susan Thomas)
This repository contains all the code files for my Master's Thesis at University of Galway, titled "Exploring Attribution Modeling in Digital Advertising"
## Contents
[Code Notebooks](code_notebooks/):This directory contains notebooks where I performed data exploration and pre-processing, attribution allocation, and evaluated prediction performance and explainability for various attribution models.
- [Data Exploration and Pre-processing](code_notebooks/0-Data%20Exploration.ipynb)
- [Traditional Attribution Models](code_notebooks/1-Traditional%20Models.ipynb)
- [Logistic Regression Model](code_notebooks/2-Logistic%20Regression.ipynb)
- [Random Forest Model](code_notebooks/3-Random%20Forest.ipynb)
- LSTM Model with Attention
  - [on original imbalanced dataset](code_notebooks/4.1-LSTM%20with%20Attention.ipynb)
  - [with class weights applied](code_notebooks/4.2-LSTM%20with%20Attention%20(with%20class-weights).ipynb)
- LSTM Model with Attention & Time Decay
  - [on original imbalanced dataset](code_notebooks/5.1-LSTM%20with%20Attention%20&%20Time%20decay.ipynb)
  - [with class weights applied](code_notebooks/5.2-LSTM%20with%20Attention%20&%20Time%20decay%20(with%20class-weights).ipynb)

[Saved LSTM Models](saved_models/): This directory includes all LSTM models that have been trained and saved during the course of this project

## Data
The data used for this project can be accessed here: [Attribution Dataset](https://www.dropbox.com/scl/fo/jrw7atq517jxzqrn2gxz5/ALfzBkRA90d2z7UmLcLqQRs?rlkey=6qg8wfcdrwuy9kfya6kejcq11&e=1&st=fh1lanzk&dl=0)
