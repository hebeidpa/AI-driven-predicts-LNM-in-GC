# AI-driven-predicts-LNM-in-GC
# This is an R-based project designed to construct and evaluate 127 machine learning models, aiming to identify gene combinations capable of predicting lymph node metastasis in gastric cancer. 
## Overview 
The project implements a complete machine learning workflow, including：
- data preprocessing
- feature selection
- model training
- prediction evaluation 
- result visualization
## Inputs
A typical dataset structure is:
```plaintext
Project Directory/
├── 📄 127model.R
├── 📄 train.csv 
└── 📄 test.csv
```
## Usage
```plaintext
source("127model.R")
```
### Outputs
```plaintext
Project Directory/
📁 output_results/               # Output Files (Auto-generated after running)
   ├── 📄 model.MLmodel.rds         # All Trained Models (RDS format)
   ├── 📄 model.riskMatrix.txt      # Risk Score Matrix
   ├── 📄 model.classMatrix.txt     # Classification Result Matrix
   ├── 📄 model.AUCmatrix.txt       # AUC Performance Matrix
   ├── 📄 model.genes.txt           # Feature Gene List
   └── 📄 model.AUCheatmap.pdf      # AUC Heatmap Visualization
```
## Acknowledgements
- We would like to express our sincere gratitude to all contributors and collaborators who supported this project. Special thanks to our research team members for their invaluable discussions and technical insights, which greatly enhanced the development and implementation of this work.
- We also acknowledge the open-source R community and developers of packages such as glmnet, randomForestSRC, xgboost, caret, and pROC. Their efforts made it possible to efficiently build and evaluate 127 machine learning models for gastric cancer lymph node metastasis prediction.
