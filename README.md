# MNIST-dataset-Digit-recognizer
Description:
The provided description explains that the dataset consists of images of hand-drawn digits, where each image is a 28x28 matrix of pixel values. Here's a more concise summary of the information:

Dataset: train.csv and test.csv
Image Format: Gray-scale images of hand-drawn digits (0 through 9)
Image Size: 28 pixels in height and 28 pixels in width, totaling 784 pixels
Pixel Values: Each pixel has an integer value between 0 and 255 (indicating lightness/darkness)
Training Data Columns: 785 columns in total
Column 1: "label" (digit drawn by the user)
Columns 2 to 785: pixel values of the associated image
Pixel Column Names: pixel0, pixel1, ..., pixel783
Pixel Location: pixel x is located at row i and column j of a 28x28 matrix, where x = i * 28 + j
