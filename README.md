# Machine Learning

I have implemented few basic algorithm of machine learning, for better understanding the concepts that we use in our everyday life as scientists and engineers. I did not include any reference from books, papers and blogs. Most of the code is my work. I used sklearn datasets.
## In: [K-Means-From-Scratch](https://github.com/ehoxha91/machine_learning_from_scratch/blob/main/kmeans_fast.ipynb)

I implemented a very fast version of K-means, which it outperforms sklearn by using vectorization and it has all the basic options. The results show that the difference is huge:

` ![Alt Text](https://github.com/ehoxha91/machine_learning_from_scratch/blob/main/thumbnail_test.png)

## In: [PCA-From-Scratch](https://github.com/ehoxha91/machine_learning_from_scratch/blob/main/pca_from_scratch.ipynb)

I implemented Principal Component Analysis from scratch. I also implemented a way to calculate an estimate of variance of the data for big datasets. I tested it with some weather data from NASA. I did not include the dataset, but I just show some maps I generated using PCA reduced data and original.

## In: [LogRegression_LinRegression_PocketPLA](https://github.com/ehoxha91/machine_learning_from_scratch/tree/main/LogRegression_LinRegression_PocketPLA) 

I implemented:

- `Pocket PLA`
- `Linear Regression`
- `Logistic Regression`

For a detailed description please read the [report](https://github.com/ehoxha91/machine_learning_from_scratch/blob/main/LogRegression_LinRegression_PocketPLA/README1.pdf).

## In: [PCA_FeatureTransform_Regularization](https://github.com/ehoxha91/machine_learning_from_scratch/tree/main/PCA_FeatureTransform_Regularization).

I implemented:

- `multiclass logistic regression with regularization`

Also used:

- `Principal Component Analysis or PCA` to reduce feature dimensions
- `Feature transform` to see how the degree of the transformation affects the accuracy, overfiting etc.

For a detailed description of the math behind the scene or the code please read the [description](https://github.com/ehoxha91/machine_learning_from_scratch/blob/main/PCA_FeatureTransform_Regularization/README2.pdf)


# Installation of required libraries

```bash 
pip3 install numpy

pip3 install pandas

pip3 install sklearn

pip3 install matplotlib
```

@EjupHoxha
