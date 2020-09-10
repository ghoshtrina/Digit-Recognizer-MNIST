# Digit-Recognizer-MNIST

The follwing project was done as part of a Data Analytics class.

The goal is to correctly identify handwritten digits. The dataset used is the famous MNIST handwritten dataset available on Kaggle. 

Data source: https://www.kaggle.com/c/digit-recognizer

The dataset contains images of handwritten digits 0 to 9. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive. So each row represents an image, with the individual pixel values in each of the 784 positions along with (or without) the label. 

The aim is to correctly identify the unlabelled digits in our test dataset. Using 2 different algorithms, Naive-Bayes Classifier and Random Forest Classifier, I chose the 'better' model for running the final predictions on the unlabelled data before submitting it to Kaggle for evaluation.

I used a 80:20 split for the labelled dataset to divide between training and validation sets.
The output had 10 different outcomes, pertaining to all 10 digits, 0 to 9. Hence, the models buiilt were multiclass classifiers.

For the first algorithm, I used the Multinomial Naive-Bayes Classifier and tuned the hyperparameters to obtain a final accuracy of 82%.
