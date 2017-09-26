# Swimming Pool IP cam snapshots analysis

Personal project to identify hours when my local swimming pool is less crammed.
There are couple of jupyter notebooks, but in short what I did is:

1. Collected publicly accessable snapshot images from my swimming pool with my tool 
[viewerby-snapshotter](https://github.com/NighTurs/viewerby-snapshotter). 
2. Labeled sample of 200 such images by hand, answering question "how much people are currently swimming".
3. Finetuned ResNet50 CNN to predict how much people are on unlabeled images.
4. Did couple of visualizations and simple time series analysis on predictions to answer my questions.
