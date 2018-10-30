# Notebooks

This is a repo for Jupyter notebooks for Udacity's [Deep Learning Course](https://classroom.udacity.com/courses/ud730).

The following APIs are used:
- Google drive v3

## Notebook 1: Data prep

- Data was downloaded, converted into 3D arrays \(Image index, x, y\) 
- Matricies were shuffled then sorted into Training, Validation, and Test datasets
- Sorted datasets were uploaded to google drive

## Notebook 2: Into the world of TensorFlow 

- Reloaded data into colab
- Introduced to Tensorflow code
- Trained multinomial logistic regression using simple gradient descent
- Added stocastic gradient descent to model, adding a Placeholder node which is updated on each run call
- Added a relu layer to model

## Notebook 3: Further on and on

- Reformat data as a flat matrix and labels as float 1-hot encodings
- Added L2 regularization for the NN and the logistic models
- Worked with a case of overfitting
- Added dropout to relu layer
 
