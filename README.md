# MNISTClassication
The “`Hello World`” of ML

Set of 70,000 small images of digits handwritten by high school students and employees of the US Census Bureau. Each of the image is labeled with the digit is represents.

Datasets loaded by Scikit-Learn generally have a similar dictionary structure, including the following:
  - A `DESCR` key describing the dataset
  - A `data` key containing an array with one row per instance and one column per feature
  - A `target` key containing an array with the labels

There are 70,000 images, and each image has 784 features. This is because each image is 28 × 28 pixels, and each feature simply represents one pixel’s intensity, from 0 (white) to 255 (black). Let’s take a peek at one digit from the dataset.
