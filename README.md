## Supplementary Materials for "Natural Language Processing Applied on Large Scale Data Extraction from Scientific Papers in Fuel Cells"

This repo hosts relevant codes for the article "Natural Language Processing Applied on Large Scale Data Extraction from Scientific Papers in Fuel Cells". We focus on the process of NLP --- including text acquisition, text preprocessing, word embedding training, and named entity recognition --- applied on 106,181 abstracts of fuel cell papers and evaluate our trained model on its ability of analogy, using the model to analyze the trend in fuel cell materials and predict new materials.

### Set up

1. Make sure you have `python3.6` and the `pip` module installed. We recommend using [conda environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
2. Navigate to the root folder of this repository (the same folder that contains README.md file) and run `pip install --ignore-installed -r requirements.txt`. Note: If you are using a conda environment and any packages fail to compile during this step, you may need to first install those packages separately with `conda install package_name`.
3. Wait for all the requirements to be downloaded and installed.

### Datasets

We use MongoDB as our dataset to store abstracts as well as word tokens after preprocessing. 
### Author

- Feifan Yang
