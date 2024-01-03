# Coastal_Satellite_Image_Classifier_CNN
This repo hosts a Convolutional Neural Network (CNN) for classification of images from coastal satellites. The model is able to distinguish between `developed` vs `natural` coastlines. There are many reasons why this automated classification might be of interest, for example, determining areas at risk of sea level rise and more.

The dataset which contains 2186 images of coastlines, was compiled by [Tom Beuzen](https://www.tomasbeuzen.com/) and can be found on Kaggle datasets [here](https://www.kaggle.com/datasets/tomasbeuzen/dsci572satellitetransfer).

Due to the computational needs to run this analysis, the original script was generated using Kaggle Notebooks to leverage Kaggle's cloud GPU. This notebook can be found [here](https://www.kaggle.com/code/arashshamseddini/coastal-satellite-image-classification-with-cnn).

A rendered copy of this script can also be found in this repo, [here](https://github.com/arashshams/Coastal_Satellite_Image_Classifier_CNN/blob/master/Analysis.ipynb).

### Dependencies

If you want to reproduce this [notebook](https://github.com/arashshams/Coastal_Satellite_Image_Classifier_CNN/blob/master/Analysis.ipynb) (`Analysis.ipynb`) on your local, simply run below commands in terminal to create the environment for running the notebook.

```
conda env create -f environment.yml
conda activate env
```
