# CLIPPR
**CLIPPR** is an algorithm that combines the top-performing **single-cell** models with RNA-inferred **copy number variation (CNV)** signals and the initial **bulk** model to create a **meta-model**, which exhibits the strongest performance in meningioma classification. It shows superior overall accuracy and resolved benign-malignant confusion. The generalizability of CLIPPR has been validated using our single-cell and bulk glioma data. CLIPPR synergizes the resolution of single-cell data with the depth of bulk sequencing, enabling improved cancer sub-group diagnoses and insights into their biology.

## Model Description
Here we developed CLIPPR, a method that predicts the meningioma classes by leveraging single-cell data and RNA-inferred CNV signal to enhance the prediction accuracy of bulk data classifiers. We demonstrate that using models trained on features learned from single-cell data accurately resolved the confusion between benign (type A) and malignant (type C) sub-groups but had limited overall accuracy. Similarly, models generated from RNA-inferred large-scale CNV signals also predicted malignant class accurately with limited overall accuracy. However, combining the top-performing single-cell models, CNV models and the initial bulk model into a meta-model resulted in the strongest performance, with superior overall accuracy and benign-malignant resolution.


## Application


