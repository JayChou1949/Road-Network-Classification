
# Classification of Urban Morphology with Deep Learning: Application on Urban Vitality

This repository is the official implementation of [Classification of Urban Morphology with Deep Learning: Application on Urban Vitality](https://arxiv.org/abs/2105.09908). It includes the major codes (written in Python) involved in the paper. We also offer some tractable tutorials in Notebook to show how to use our two modules, `CRHD generator` and `Morphoindex generator`. `CRHD generator` can automatically produce Colored Road Hierarchy Diagram (CRHD) for a given urban area. `Morphoindex generator` can automatically generate both traditional morphological indices based on built environment Shapefiles and road network class probabilities based on our road network classification model.

## Requirements

To use `CRHD generator`, you need to install the requirements:

```setup
pip install osmnx
pip install geopandas
pip install matplotlib
```
To use `Morphoindex generator`, you need to install the additional requirements:

```setup
pip install tensorflow
pip install keras
pip install cv2
pip install numpy
```

## Training


## Pre-trained Models

You can download our pretrained models here:

- [Road network classification model](https://drive.google.com/mymodel.pth) trained on our labelled image set using ResNet-34 architecture, learning rate as 0.0005, batch size as 2. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 
