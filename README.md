# ai_flowering

This repo contains code for classifying images as containing flowers or not containing flowers. 

To reproduce analyses, download or clone this repo, download images from iNaturalist, and run the Python code found in transfer_learning_flowering_v3.ipynb. This Python notebook is adapted from the Sasank Chilamkurthy's Transfer Learning for Computer Vision Tutorial (https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html).

Briefly, here are the steps implemented in the code: 

Import packages.

Load data and organize into folders. 

Train model using transfer learning with fine-tuning. 

Use model to make predictions for labeled and unlabeled images. Add iNaturalist metadata to predictions. iNaturalist metadata are available for download from inaturalist.org; the metadata used for this analysis are in this repo in data/iNaturalistEucalypts - iNaturalistEucalypts.csv. 

Using transfer learning with the pretrained model as a fixed feature extractor. This model was less accurate and therefore we did not use it.   
