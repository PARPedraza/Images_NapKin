from pathlib import Path

# Contenido del archivo README.md
readme_content = """
# 📊 Timeline of AI Methods Applied to *Hibiscus sabdariffa* Studies

This visualization was created using **[Napkin](https://napkin.io/)** to illustrate the evolution of artificial intelligence methods employed in research articles involving *Hibiscus sabdariffa*. 

## 🔍 Data Source and Methodology

The timeline was developed as part of a **systematic review** that analyzed scientific publications meeting the following **two inclusion criteria**:

1. The study must explicitly focus on *Hibiscus sabdariffa* (commonly known as roselle).
2. The study must apply **Artificial Intelligence (AI)** techniques, such as machine learning, deep learning, fuzzy logic, or hybrid models.

Following article selection and screening, we compiled and grouped the AI methods used by year of publication. Each method appears under the first year it was reported in the included studies. The resulting visualization highlights the progressive adoption of AI techniques in the scientific study of *H. sabdariffa*, across diverse domains including agriculture, food science, pharmacology, and environmental modeling.

## 📆 Methods per Year

- **2013**: ANN, PLS  
- **2014**: ACO-PLS, GA-PLS  
- **2015**: MaxEnt  
- **2019**: RSM, ANN, ANFIS  
- **2020**: Naive Bayes, PNN, SVM, Fuzzy Logic, MFEF/MNFF  
- **2021**: ANN  
- **2022**: MGGP, Ward, PCA, FFNN / Levenberg–Marquardt  
- **2023**: PLS, PCR, KNN, ANN  
- **2024**: Fusion Model, Decision Tree, K-Means, ResNet, DenseNet, VGG, ConvNeXt, Swin Transformer  
- **2025**: Adaptive Boosting, Support Vector Regressor, Ridge Regressor, Lasso Regressor, Random Forest Regressor, Multi-Layer KNN Regressor, Gradient Boosting

## 🛠 Final Design Step

Although the timeline was initially generated in Napkin for clarity and visual aesthetics, **a final manual adjustment was performed** to ensure correctness. This step was necessary because **Napkin may output misaligned or incomplete labels**, so the exported image was **refined and verified** to match the actual dataset derived from the systematic review.
"""

# Ruta para guardar el archivo
file_path = Path("/mnt/data/README_Hibiscus_Timeline.md")

# Guardar el contenido en el archivo
file_path.write_text(readme_content)

file_path.name
