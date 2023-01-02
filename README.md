# Optimisation of a Video Game Recommendation System.

This repository contains the code I re-implemented SLi-Rec model from [Microsoft](https://github.com/microsoft/recommenders/) for the NTU x Ubisoft EDGE Programme. 

As the **[provided dataset]** from Ubisoft has some similar features with the Amazon Reviews dataset so I used:
- `recommenders/datasets/amazon_reviews.py` for pre-processing the dataset
- `recommenders/models/deeprec/config/sli_rec.yaml`: this configuration file contains information of many hyperparameters for SLi-Rec

Notebooks:
- `dataset_preparation.ipynb`: pre-process the **[provided dataset]** to get the exact format as Amazon dataset for applying the SLi-Rec easily.
- `training_vs_evaluating_slirec.ipynb`: train and test model on the pre-processed **[provided dataset]** with 5.2M transactions. All of the markdown notes can be found inside this notebook.