# Automatic_Review_Analyzer
## This Project is part of the MITx MicroMasters in Statistics and Data Science
The goal of this project is to design a classifier to use for sentiment analysis of product reviews. 
Our training set consists of reviews written by Amazon customers for various food products. The reviews, 
originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

Below are two example entries from our dataset. Each entry consists of the review and its label. The two reviews were written by different customers describing their experience with a sugar-free candy.

For example:

"Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again" will be flagged -1
"YUMMY! You would never guess that they're sugar-free and it's so great that you can eat them pretty much guilt free! i was so impressed that i've ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT!" will get +1 on the other hand

In order to automatically analyze reviews, we need to complete the following tasks:

1. Implement and compare three types of linear classifiers: the perceptron algorithm, the average perceptron algorithm, and the Pegasos algorithm.

2. Use your classifiers on the food review dataset, using some simple text features.

3. Experiment with additional features and explore their impact on classifier performance.


project1.py contains various useful functions that will be used to implement your learning algorithms.

main.py is a script skeleton where these functions are called and you can run your experiments.

utils.py contains utility functions that the staff has implemented for you.

test.py is a script which runs tests on a few of the methods we implement. Note that these tests are provided to help debug our implementation.
