# info251_finalproject

## Note on Datasets
- The datasets exceed Github's maximum file size. However, they can be downloaded from Kaggle here: https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces and here: https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection. See below for how to download the files into your Colab environment.

## Instructions for running our code
- Load our .ipynb notebooks into Google Colab (highly recommended since we're running several neural network and CNN models which would otherwise take hours to run on CPU)
- Enable GPU boost on Google Colab
- Run the code in the notebook to download data and unzip to the Colab VM environment (we provide 2 options -- 1 using the Kaggle API, the other by mounting a Google Drive). For development, we found that mounting from a Google Drive was better so we didn't have to download the datasets each time. The Kaggle API is an option if you're trying to just run the code once. 
- Run the rest of the notebook cells
- If you want to skip training and just predict with our models, you can load our saved Models (see folders with saved .h5 models). However, these .h5 models do not include training history (no accuracy/loss plots).

## included here
- Analysis code (the .ipynb files)
- Saved models (in .h5 format, can just load these with Keras to skip training)
- Report video
- Final report
- CSVs with filenames and paths (but not the data itself!). Please see our Google Drive (shared w/ instructor) for full datasets.