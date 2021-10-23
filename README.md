## NTUxUbisoft EDGE Programme: Optimisation of a Video Game Recommendation System.

My work is based on the SLi_Rec model from [Microsoft](https://github.com/microsoft/recommenders/blob/main/examples/00_quick_start/sequential_recsys_amazondataset.ipynb)

Folders `recommenders` and `tests` are from Microft. As one file may use inherits from many other files, I do not remove any unused files and keep most of them unchanged except:
- `recommenders/datasets/amazon_reviews.py`: this is for data processing part.
- `recommenders/models/deeprec/config/sli_rec.yaml`: this .yaml file contains information of many hyperparameters for SLi_rec

Notebooks I created:
- `dataset2_prepare.ipynb`: pre-process the original dataset to get the same format as Amazon dataset (used by Microsoft).
- `slirec_on_sampled_dataset 2.ipynb`: train and test model on a sampled dataset with 1.4M transactions.
- `slirec_on_whole_dataset2.ipynb`: train and test model on the whole dataset with 5.2M transactions. Note that there is no markdown in this notebook so please refer to markdowns in the sampled_dataset notebook when in doubt.
