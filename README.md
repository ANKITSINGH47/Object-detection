# Object Localization and classification using Tensorflow
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
We employ localization loss function as Binary cross Entropy  to train the model. The localization loss ensures accurate bounding box predictions 

## Training:
The model is trained on the dataset using TensorFlow's optimization techniques, Adam optimizer.






<br>

# Object Detection using ResNet16 

<img width="631" alt="object-detection1" src="https://github.com/ANKITSINGH47/Object-detection/assets/47277960/46dedd95-0b9d-49b3-8255-f724f611b06b">
<br>

<img width="611" alt="obj-det-2" src="https://github.com/ANKITSINGH47/Object-detection/assets/47277960/e2e417cd-786c-4dde-8ea6-0c8f4a99f7f8">  

## Introduction:
Object detection is a crucial task in computer vision, enabling machines to identify and locate multiple objects within an image. TensorFlow provides a flexible and powerful platform for developing object detection models. This paper focuses on two popular models: SSD, known for its real-time capabilities, and ResNet V1, recognized for its feature extraction prowess. We evaluate their pretrained versions to analyze their applicability in real-world scenarios.

## Models:
We employ the SSD and ResNet V1 pretrained models available in the TensorFlow Model Zoo. These models are trained on large-scale datasets, making them suitable for a wide range of object detection tasks.


## Evaluation Metrics:
We use standard metrics such as Precision, Recall, and Mean Average Precision (mAP) to quantitatively assess the performance of the models. These metrics provide insights into the models' ability to balance accuracy and efficiency.

## TensorFlow Setup:
We provide details on setting up TensorFlow and loading the pretrained SSD and ResNet V1 models from the TensorFlow Model Zoo. This includes necessary dependencies and configurations for seamless integration.

## Inference Pipeline:
We outline the steps for running object detection on input images using the pretrained models. This includes preprocessing, model inference, and post-processing to visualize and analyze the detection results.





















































































