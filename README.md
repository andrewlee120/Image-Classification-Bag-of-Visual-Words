# Image-Classification-Bag-of-Visual-Words

- Andrew Lee and Jacky Yuan -

Taking images of cats and dogs, we perform machine learning to identify whether a cat or a dog is present in an image. We first extract features from the images using the SIFT algorithm. These features are represented by descriptors (vectors of length 128). We perform K-means clustering to group the descriptors into 200 clusters. For each image, we calculate how many features belong to each cluster and produce a histogram based on that data. Using the data from the histogram, we can use our learning models to classify our images.

The learning models used in this project are logistic regression, support vector machine, and neural network.
