Amyotrophic lateral sclerosis (ALS) Processing
==============================================

This repository contains the implementation of our study titled **"Comparing Machine Learning and Deep Learning Approaches for ALS Diagnosis Using Blood-Derived Biomarkers and Synthetic Data"**.

![Abstract](abstract.jpg)

## Authors

- **Ali Salman** - Department of Medical Biotechnologies, University of Siena, Italy
- **Matteo Leoncini** - Department of Medical Biotechnologies, University of Siena, Italy
- **Amedeo Amedei** - Department of Clinical and Experimental Medicine, University of Florence, Florence, Italy
- **Ernesto Iadanza** - Department of Medical Biotechnologies, University of Siena, Italy

## Abstract

Amyotrophic lateral sclerosis (ALS) is a progressive neurodegenerative disorder primarily targeting motor neurons. Emerging research highlights the potential of blood-derived biomarkers (BDBs) for early diagnosis and tracking disease progression. This study evaluates the efficacy of machine learning and deep learning algorithms in differentiating ALS patients from healthy controls (HC) using BDBs as input features. To address the challenge of limited and imbalanced real-world data, we generated synthetic datasets with sizes 10x and 20x larger than the real dataset, ensuring balanced class distributions. The models were exclusively trained on synthetic data and evaluated on real data. Among the models, the LightGBM classifier achieved the highest performance, with an accuracy of 98.31%, an F1 score of 98.96%, and an AUROC of 99.80% when trained on the 20x synthetic dataset. These results underscore the promise of synthetic data in enhancing diagnostic capabilities for ALS through computational approaches.

## Citation

If you use this work, please cite it as:

```bibtex
@misc{salman2025als_ml_dl,
  author       = {Ali Salman and Matteo Leoncini and Amedeo Amedei and Ernesto Iadanza},
  title        = {Comparing Machine Learning and Deep Learning Approaches for ALS Diagnosis Using Blood-Derived Biomarkers and Synthetic Data},
  year         = {2025},
  institution  = {Department of Medical Biotechnologies - University of Siena, Siena, Italy},
  note         = {Available on GitHub: https://github.com/alexsalman/GNB2025},
  url          = {https://github.com/alexsalman/GNB2025},
  urldate      = {2025-01-20}
}

