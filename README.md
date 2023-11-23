# Object Localization and classification 
## White box Localization
<img width="314" alt="box-detection" src="https://github.com/ANKITSINGH47/Object-detection/assets/47277960/8b3e17f3-6eb6-49e9-8b59-96b44dd3c863"> <br>
Object localization is a critical task in computer vision, enabling machines to not only recognize objects in an image but also determine their spatial location. White box localization involves gaining insights into the internal workings of a model to understand how it makes predictions. Here we explored white box localization on a black background using TensorFlow, a popular open-source machine learning library. The aim is to shed light on the interpretability of object localization models and their performance in scenarios where the background black.


## Introduction 
Object localization plays a pivotal role in various applications, including autonomous vehicles, robotics, and image understanding. While black backgrounds are uncommon in real-world scenarios, understanding how object localization models perform in such conditions can provide valuable insights into their robustness and generalization capabilities. Here we focusesed on using TensorFlow, an open-source machine learning framework, to implement and analyze a white box object localization model on a black background.

## Dataset:
To conduct our experiments, we utilize a custom dataset containing images with white box positioned on a black background. The dataset includes a diverse set of white box locaations with different shape and locations to ensure the model's ability to generalize.


## Model Architecture:
We employ a convolutional neural network (CNN) as the base architecture for object localization. The architecture is designed to have a transparent structure, allowing for detailed examination of internal representations during the white box analysis. TensorFlow's high-level API facilitates the construction of the model.

## Loss Function:
We employ localization loss function as Binary cross Entroopy  to train the model. The localization loss ensures accurate bounding box predictions 

## Training:
The model is trained on the dataset using TensorFlow's optimization techniques, Adam optimizer. We analyze the convergence and performance metrics to evaluate the model's learning behaviour


































































<img width="631" alt="object-detection1" src="https://github.com/ANKITSINGH47/Object-detection/assets/47277960/46dedd95-0b9d-49b3-8255-f724f611b06b">





























<img width="611" alt="obj-det-2" src="https://github.com/ANKITSINGH47/Object-detection/assets/47277960/e2e417cd-786c-4dde-8ea6-0c8f4a99f7f8">





