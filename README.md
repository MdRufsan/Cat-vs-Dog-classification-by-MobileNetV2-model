Cat vs Dog Image Classification
Overview :

This project builds an image classification model that can identify whether an image contains a cat or a dog. The model is developed using TensorFlow and MobileNetV2 through transfer learning. The final model achieves an accuracy of approximately ninety eight percent on the validation dataset.

Features :

Uses MobileNetV2 pretrained on ImageNet
Applies transfer learning and fine tuning
Achieves high accuracy
Uses clean and modular TensorFlow code

Dataset :

The project uses the Cats versus Dogs dataset from TensorFlow Datasets. The dataset is loaded with an eighty percent training split and a twenty percent validation split.

Model Architecture :

The model is built using the following components
MobileNetV2 as the base model
Global average pooling layer
Dense layer with two hundred fifty six units
Dropout layer
Final dense layer with two units for the two classes

Training Process:

Step one
The MobileNetV2 base model is frozen and trained for one epoch
Step two
The base model is unfrozen after layer number one hundred and fine tuned using a very low learning rate. An early stopping callback is added to prevent overfitting.

Training Results:

The initial training achieved an accuracy above ninety six percent and a validation accuracy above ninety eight percent.
After fine tuning the final model achieved an accuracy of approximately ninety eight percent.

Evaluation :

The model is evaluated on the validation dataset and prints the final accuracy.

Installation :

Install the required packages before running the project

pip install tensorflow keras tensorflow datasets

Usage :

Run the training script or notebook to train the model.


Folder for model outputs

Author

This project is created by MD Rufsan Jani Shanto.
