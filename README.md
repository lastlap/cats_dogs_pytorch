# Cats and dogs classifier using Pytorch

Uses GPU for training
We use a [dataset of cat and dog photos](https://www.kaggle.com/c/dogs-vs-cats) from Kaggle.
Download the structured dataset from [here](https://s3.amazonaws.com/content.udacity-data.com/nd089/Cat_Dog_data.zip).

Once that is done we can run train.py to start the training.
We use a pretrained densenet121 model and train only the classifier.

After training you can test on single images using
```
python test.py --img_path="path_to_your_image"
```
