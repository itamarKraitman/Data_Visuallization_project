## Data Visualization Project 

In this project, I worked on four notebooks, each notebook with a different target.

#### __**Notebook number one**__
The first notebook is the continuation of the classification notebook where I started [here](https://github.com/itamarKraitman/Machine-Learning-Project/blob/main/Classification%20notebook.ipynb). The challenge is to improve the accuracy of this notebook using methods and
algorithms I learned after creating the first notebook. In this notebook, I dealt with imbalanced data
and used PCA. In addition, I trained several models such as RandomForest,
Bagging, AdaBoost, XGBoost, knn, and Stacking.

![Screenshot_1](https://user-images.githubusercontent.com/73484628/178473106-6d28431e-47fb-4d93-a5e6-2f5ba78c36a5.png)


#### __**Notebook number 2**__
In the second notbook, I dealt with the [fashion MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist) dataset. Gray scaling wasn't needed
because the images are already in black and white. After visualizing I applied PCA. In
this notebook, I used several models such as LogisticRegression, RandomForest,
AdaBoost, XGBoost, and Voting. Finally, I tested the best model with the test data set.

![Screenshot_2](https://user-images.githubusercontent.com/73484628/178473360-72ada319-a38d-4072-bca4-b00ba43c6af6.png)
![Screenshot_3](https://user-images.githubusercontent.com/73484628/178473377-af241985-c8de-43e4-b7d0-047ba4d9f9fb.png)


#### __**Notebook number 3**__
In the thirs notebook I tired to obtain high accuracy of classifying [dogs vs cats](https://www.kaggle.com/c/dogs-vs-cats) data set. In this notebook, I
decided not to convert the images into grayscale for the simple reason that after grayscaling
the results were worse than before. In this notebook, I applied PCA with 0.95
components and trained some models. In this notebook, I used several models such as:
logisticRegression, XGBoost, Stacking, and Voting.

![Screenshot_4](https://user-images.githubusercontent.com/73484628/178473583-a382231a-75fe-458c-8e0d-79985c09d653.png)


#### __**Notebook number 4**__
In this notebook, the targeet was to classify between three ways of communication between people. The first is spontaneous, when people move their hands  spontaneously, synchronized, when people move their hands in sync, and alone, when a person moves his hands with no one else in front of him.<br/><br/>
This notebook was the trickiest stage in this project, for the reason it required a lot of
self-learning and diving deep into pandas, but I feel I cope with it in a pretty good way
and got good results. The first step I took, was to upload both training data and validation
data to work on them simultaneously, I created two lists, one for each set
because I believed it will be easier for me to work in this way. Secondly, using pandas I
perform some methods to process the data sets to meet the requirements the lecurer
wrote in the instruction for this project. The next step I took was to apply PCA with
four different numbers of components- 0.8,0.85,0.9,0.95 (meanwhile I noticed that 0.8
and 0.85 had almost the same results with only minor differences so I drop 0.8) and
trained several models (same models on each percent) to catch the percent that
will give me the best scores along with the smallest number of features. The
appropriate percent turned out to be 0.95 with 12 features out of 20 (three features were
dropped before). Lastly, I tested the best model with the validation set. The models I
used in this notebook are knn, RandomForest, XGBoost, AdaBoost, and Stacking.
