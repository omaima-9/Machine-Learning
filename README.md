# Machine-Learning

Machine Learing projects

## 1- least squares-based classification algorithm

a least squares-based classification algorithm that can recognize
the Iris flower type in the Iris dataset. The objective is to classify each data point (row) in the file
“Test.csv” to one of the three types of flowers (Setosa, Versicolor, or Virginica) using the
least squares classifier

## 2- Perceptron-based classification algorithm

a Perceptron-based classification algorithm that can recognize scanned images of the 10 digits (0 to 9). The Training images should be used to
train a classifier for each digit. a file named “Training Labels.txt” which includes the labels of the 2400 images.
For all Perceptrons, an initial weight vector was useed that has 1 as the first component (w1) and the rest are zeros. To include the bias term,
I appended a constant value equal to 1 to all input vectors and adjusted the size of the weight vector accordingly.

## 3- K-means clustering algorithm

One important aspect of K-means that changes the results significantly is the initialization. A good strategy for initializing cluster centers is as follows:
1- Pick one of the dataset points randomly as the center of the first cluster
2- For the next cluster, find the point with maximum distance to the center of the previous cluster
3- Choose this point as the center of the next cluster
4- Repeat steps 2 and 3 until you initialize the centers of all cluster
