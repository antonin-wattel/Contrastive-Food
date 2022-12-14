
# Contrastive Food

In this project, we propose a model that can retrieve a recipe from a list of known recipes given an image query and, in reverse, retrieve an image from a list of known images given a text recipe. This model consists of an image encoder and a text encoder trained in a contrastive setting. More details can be found in the [project report](report.pdf)

This project was realised by Antonin Wattel in the context of the course INF634 - Computer Vision, by Vicky Kalogeiton.

# Requirements

A CUDA-capable device is required to run this project.

Dependencies:
```
    torch
    torchvision
    scikit-learn
    matplotlib
    numpy
    pandas
    PIL 
    transformers
    tqdm
```

Optional dependencies:

```
    wandb 
    clip (https://github.com/openai/CLIP.git)
```


## Environment setup

The required dependencies can be installed using the following command

```
    conda env create --name=contrastive_food --file=environment.yaml
```

## Data

the *Food and Ingredients Dataset can be downloaded* [here](https://www.kaggle.com/datasets/pes12017000148/food-ingredients-and-recipe-dataset-with-images/download?datasetVersionNumber=1).

To use it, unzip it under the `data` folder.

# Usage

A step by step for training, evaluation, and additional visualization functions are found in the jupyter notebook [`notebook.ipynb`](notebook.ipynb)



