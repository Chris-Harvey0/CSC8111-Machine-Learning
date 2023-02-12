# CSC8111-Machine-Learning
## Overview
This project involved picking two datasets from the available four.
The task was then to develop machine learning pipelines for the picked datasets and to compare results.
I picked the image dataset CIFARTile, and the text dataset of Tweets to airline companies.
## Image Dataset
This dataset was created for a competition where the average accuracy obtained was only 45%.
After a lot of optimisation of my model I came up with the model shown in CSC8111_Image_Dataset.ipynb which obtained an accuracy of 53% on a good run.
This was satisfactory for this task as it was higher than the average from the competition and was far better than the accuracy from my original model which was much simpler.
## Text Dataset
This dataset included Tweets sent to airline companies.
These Tweets had not been cleaned at all, so this was a problem I had to overcome.
I removed all non-English characters and used several other methods commonly used in natural language processing.
Once this was complete I ran the words through a random forest classifier to decide whether the Tweets were positive, neutral or negative.
This random forest classifier obtained an accuracy of 77%.
Because this model was simple to implement I decided to implement another style of model and compare results.
I chose to implement a long short term memory model which is commonly used for natural language processing.
This model gave improved accuracies over the random forest model of 78%.
## Reflection
In this project I developed machine learning models for two different datasets.
The model for the Tweets dataset managed to obtain relatively good results of 78%.
However, for the image dataset 53% was the maximum accuracy obtained.
I was still very happy with this accuracy as it beat the average accuracy from the machine learning competition it was used for.
For future work I would aim to improve this accuracy by using various image augmentation techniques to improve accuracy further.
