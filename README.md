# K_nn-Analsysis-on-Prostate-Cancer
A classification project using the Kth Nearest Neighbours algorithm to determine if given a few data points, a patient has a cancerous vs non-cancerous tumour.

The dataset I used was the Prostate_cancer.csv dataset which contains information of n=100 patients each with its own diagnosis result (0 representing a malignant tumour, and 1 representing a benigin tumour), radius, texture, perimeter, area, smoothness, compactness, symmetry, and fractal dimension. Using the data categories, I attempted to predict the diagnosis. 

This was done using the Kth Nearest Neighbour algorithm by taking columns two and onwards (data points), and testing with the results in column one (diagnosis) with a computed K value of 3.

After conducting the test, both the f-score, and accuracy test were 1.0, likely caused by the similarities present in the training, and testing sets due to the patients having similar or near similar data points. 
