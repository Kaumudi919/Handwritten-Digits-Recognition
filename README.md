### Handwritten-Digits-Recognition

#### Problem Statement:
The goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. Using the different algorithms to learn first-hand what works well and how techniques compare.<br>

#### Dataset:
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
To the get the data for this project please follow the below code:<br>
from tensorflow.keras.datasets import mnist<br>
(x_train, y_train), (x_test, y_test) = mnist.load_data()<br>
The input feature contains images.<br>
Output feature contains 10 classes (digits varying from 0 to 9).<br>
Each image is a 28 by 28 pixel square(784 pixel total). The dataset contains 60,000 images for model training and 10,000 images for the evaluation of the model.<br>

#### Model building:
| Model | Accuracy |
|-------|----------|
| Logistic Regression| 84% |
| SVM | 93% |
| KNN | 94% |
| CNN | 98% |

