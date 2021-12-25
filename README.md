# Fashion_MNIST_Classification
A deep learning fashion images classifier developed by using the Keras framework and the Fashion-MNIST dataset.

## DATASET<br/>
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

![Fashion-MNIST-Dataset-Images-with-Labels-and-Description-II-LITERATURE-REVIEW-In-image](https://user-images.githubusercontent.com/96647191/147389598-ea18f014-3ec2-4da8-a122-95a5b10170aa.jpg)

## problem
• The objective is to identify (predict) different fashion products from the given images using Convolutional neural network.<br/>
• The ‘target’ dataset has 10 class labels, as we can see from above (0 –T-shirt/top, 1 –Trouser,,....9 –Ankle Boot).<br/>
• Given the images of the articles, we need to classify them into one of these classes, hence, it is essentially a‘Multi-class Classification’problem.<br/>

## Methodology
• preprocessing- it involves changing the dimension and scaling of images<br/>
• buliding the model<br/>
• testing and evaluating the model<br/>

## Scoring

simple model:
overall accuracy: 89.4568

complex model:
overall accuracy: 90.28000

## confucion matrix

<img width="332" alt="image" src="https://user-images.githubusercontent.com/96647191/147389768-faed9fe6-b8ad-4351-ab78-b3bd2227f5c2.png">
<br/>
<img width="314" alt="image" src="https://user-images.githubusercontent.com/96647191/147389777-0d8bdbc2-afd3-4a73-858a-9074af32523c.png">
