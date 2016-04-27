# Image Classification in MATLAB

tags: Machine Learning

In this project, our goal was to build a system that recognizes and classifies the object present in an image of size 231x231. We were given a set of training images each with one of four labels: 1 for airplanes; 2 for cars; 3 for horses; 4 otherwise. We were provided with two sets of features: one is Histogram of Oriented Gradients (HOG), which has dimension of 5408; the other one is OverFEAT ImageNet CNN Features, which has dimension of 37,000. Concerning the test images, we were only given the features of each image without label, and the results to be judged by the grader. Our goal was to provide binary and multiple predictions. The Balanced Error Rate (BER) was our performance evaluator. To solve the problem, we firstly reduced the problem’s dimensionality by PCA, dealt with imbalanced datasets through up-sampling or down-sampling, and removed outliers through unsupervised learning such as K-Means and EM Algorithm. Secondly, we applied ML methods such as Binary and Multinomial Logistic Regression, Binary and Multinomial SVM's and Neural Networks. Multinomial SVM's proved to have the best results. Finally, We scored 92 out of 100.