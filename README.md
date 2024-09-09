# Stance Detection

## Dataset

- <https://www.kaggle.com/datasets/arashnic/7-nlp-tasks-with-tweets/data>

## Installing

```zsh
# create conda env
conda env create -f env.yml 
conda activate stance

# alternative pip install
pip install tensorflow==2.12.0 transformers==4.27.3 scikit-learn==1.1 pandas==1.4.4 matplotlib==3.9.2 ipykernel==6.29.5 numpy==1.23.5

# remove env
conda deactivate
conda env remove --name stance
```
