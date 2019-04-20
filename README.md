# Fashion_MNIST

The Fashion MNIST dataset was created by e-commerce company, Zalando.It is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

![mnist](https://user-images.githubusercontent.com/41579652/56460242-4b9c1600-63bd-11e9-868e-855f64e27857.gif)

## Problems with the Standard MNIST Digit Recognition Dataset:
1. It’s far too easy for standard machine learning algorithms to obtain 97%+ accuracy.
2. It’s even easier for deep learning models to achieve 99%+ accuracy.
3. The dataset is overused.
4. MNIST cannot represent modern computer vision tasks.

*Zalando, therefore, created the Fashion MNIST dataset as a drop-in replacement for MNIST. The Fashion MNIST dataset is identical to the MNIST dataset in terms of training set size, testing set size, number of class labels, and image dimensions.*

## Why we made Fashion MNIST

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Fashion-MNIST is intended to serve as a drop-in replacement for the original MNIST dataset, helping people to benchmark and understand machine learning algorithms. It encourages researchers to design unequivocal experiments to understand algorithms better.

![comp](https://user-images.githubusercontent.com/41579652/56460291-2e1b7c00-63be-11e9-9556-357c8fea8ac6.JPG)

## Prerequisites

We would highly recommend that before the hack night you have some kind of toolchain and development environment already installed and ready. If you have no idea where to start with this, try a combination like:
- Python
- scikit-learn / sklearn
- Pandas
- NumPy
- matplotlib
- An environment to work in (something like Jupyter or Spyder)

For Linux people, your package manager should be able to handle all of this. If it somehow can't, see if you can at least install Python and pip and then use pip to install the above packages.

## Dataset Description

- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
- Each pixel has a single pixel value associated with it, indicating the lightness or darkness of that pixel(higher numbers meaning darker).
- The pixel value is an integer between 0 and 255.
- The training and testing datasets have 785 columns.
- The first column in the dataset consist of class labels which represents the article of clothing.
  ![label_desc](https://user-images.githubusercontent.com/41579652/56460399-b0587000-63bf-11e9-99a3-1c93f700ccd3.JPG)
- The rest of the columns contain the pixel values of the associated image.
  - To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix.
  - For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top.
  
## Objectives
- View the data as an image
- Train different classifiers
- Compare performance for different classifiers using various metrics

## Dataset

The dataset is in the form of a csv file:

https://drive.google.com/file/d/1eeJu_0kXJnCFcn_sikhvQ7h2iKbZwpt9/view?usp=sharing/

![info](https://user-images.githubusercontent.com/41579652/56461130-4cd43f80-63cb-11e9-8a82-b30df9a4e27a.JPG)

## Libraries Used
- pandas
- matplotlib.pyplot
- seaborn
- sklearn

## Viewing data according to class label

![clothing](https://user-images.githubusercontent.com/41579652/56461301-f4527180-63cd-11e9-9ded-21b69227eddc.JPG)

## Training Models Used:

- Logistic Regression
- KNN (K Nearest Neighbors)
- Random Forest
- SVM (Support Vector Machine)

## Performance Metrics Used :

- Accuracy Score
- Confusion Matrix
- Classification report








  





