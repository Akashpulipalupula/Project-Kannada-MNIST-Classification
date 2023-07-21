# Project-Kannada-MNIST-Classification

# Problem Statement: 
This is an extension of classic MNIST classification problem. Instead of using Hindu numerals, let’s use a recently-released dataset of Kannada digits. This is a 10 Class classification problem.
Kannada is a language spoken predominantly by people of Karnataka in southwestern India. The language has roughly 45 million native speakers and is written using the Kannada script. https://en.wikipedia.org/wiki/Kannada
Dataset is downloaded from the link: https://www.kaggle.com/datasets/higgstachyon/kannada-mnist.
All details of the dataset curation have been captured in the paper titled: Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language. " https://arxiv.org/abs/1908.01242

# Procedure:
1. Extracting the dataset from the npz file from the downloaded dataset. There are 60000 images for training and 10000 images for test. Each image is of the size 28X28.
2. Perform PCA to 10 components. So now we have train and test images in 10 dimensions instead of 28X28 dimension.
3. Now apply the following models:
• Decision Trees
• Random forest
• Naive Bayes Model
• K-NN Classifier
• SVM
4. For each of this method produce the following metrics:
• Precision, Recall, F1 - Score
• Confusion Matrix
• RoC - AUC curve
5. Repeat the same experiment for different component size: 15,20,25,30
