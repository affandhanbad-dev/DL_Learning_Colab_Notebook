📌 MNIST Handwritten Digit Classification

This project demonstrates how to load, explore, preprocess, and visualize the MNIST handwritten digit dataset using TensorFlow and Keras.
The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0–9) resized to 28 × 28 pixels.

🧠 Objective

To understand:

How to load the MNIST dataset in Keras

Visualize image data

Normalize image pixel values

Explore the dataset statistics

📂 Dataset

The dataset is automatically downloaded from keras.datasets.mnist.

Split	Images	Shape
Training	60,000	(28, 28)
Testing	10,000	(28, 28)
🛠️ Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Seaborn

OpenCV (for image processing)

PIL

🚀 Steps Performed
✅ Import Libraries

Essential libraries for data processing, visualization, and TensorFlow model utilities.

✅ Load Dataset
(X_train, Y_train), (X_test, Y_test) = mnist.load_data()

✅ Visualize an Example Digit
plt.imshow(X_test[0])
plt.show()
print(Y_test[0])


✅ Output → A handwritten digit (e.g., 7)

✅ Validate the Dataset Classes

Ensures dataset contains digits ➝ 0 to 9

print(np.unique(Y_train))
print(np.unique(Y_test))

✅ Pixel Normalization

To improve neural network training performance, pixel values are normalized from 0-255 to 0-1.

X_train = X_train / 255
X_test = X_test / 255

🔍 Sample Output Preview
Before Normalization	After Normalization
uint8 values	float values
Range: 0–255	Range: 0–1
📊 Result

Data successfully loaded and visualized

ML preprocessing step completed

Ready for building and training classification models like
✅ Neural Networks
✅ CNNs
