# Satellite-Image-Classification
Using deep learning techniques to classify land use patterns from satellite image data. A resnet34 CNN is implemented in Fastai. With minimal tuning the model achieved a 0.93 accuracy score, however there were a few category pairs where the learner had trouble, namely:

- 38 'Highway' images classified as 'Rivers'
- 37 images of 'PermanentCrop' classified as 'HerbaceousVegetation'
- 24 images of 'Pasture' classified as 'HerbaceousVegetation'

The dataset comes from EuroStat Sentinel-2 satellite images and can be found here: http://madm.dfki.de/downloads


