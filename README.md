If need dataset go to kaggle.com and download any dataset.

1. Data Loading:
• We started by loading the MNIST-Fashion dataset from CSV files. The dataset contains images of clothing items, each labelled with a specific category.

2. Display Example Images:
• We displayed a few example images from the dataset to visualize the clothing items. This step helped us understand the nature of the dataset and the types of images we were working with.

3. Sampling Subsets of Different Sizes:
• We wrote a function to sample subsets of different sizes from the training split. These subsets represent different training set sizes, ranging from 0.1% to 10% of the original training dataset size.

4. Training Classifier and Scoring:
• We implemented a function to train a classifier using each sampled subset. The classifier consisted of two main steps: PCA (Principal Component Analysis) for dimensionality reduction and kNN (K Nearest Neighbours) for classification.
• After training the classifier on each subset, we scored it on the test set to calculate the classification
accuracy.

5. Plotting Accuracy vs Training Set Size:
• Finally, we plotted the test accuracy against the training set size. This plot showed how the
classification performance varied with different training set sizes.
• The plot helped us analyse the impact of training set size on the classifier's performance and
understand whether more training data resulted in better classification accuracy.

Summary:
Overall, we addressed the problem by loading the dataset, displaying example images, sampling subsets of different
sizes, training classifiers, scoring them on the test set, and plotting the results. This approach allowed us to
systematically explore the relationship between training set size and classification performance for the MNIST-Fashion dataset.
