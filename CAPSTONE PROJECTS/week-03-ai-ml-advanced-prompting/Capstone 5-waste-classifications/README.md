Project Scenario: Smart Waste Classification System
A city municipality wants to build an AI-powered waste segregation system that can automatically classify images of waste into:

Recyclable Waste

Organic Waste

Non-Recyclable Waste

You are required to build a deep learning image classifier that can perform this task.

Task 1 – Dataset Collection (5 Marks)
Download or collect a dataset of waste images from sources 

https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification?utm_source=chatgpt.com


Organize the dataset into the following folder structure:

dataset/

   train/

       recyclable/

       organic/

       non_recyclable/


   validation/

       recyclable/

       organic/

       non_recyclable/


Deliverable:
• Show the dataset structure and total number of images in each class.

Task 2 – Data Preprocessing (5 Marks)
Perform the following preprocessing steps:

Resize images to a fixed size (e.g., 224×224)

Normalize pixel values

Apply data augmentation (at least 3 techniques)

Examples:

Rotation

Horizontal flip

Zoom

Brightness adjustment

Deliverable:
• Show the preprocessing pipeline code.

Task 3 – CNN Model Development (8 Marks)
Build an image classification model using CNN.

Your model should include:

Convolution layers

Pooling layers

Dense layers

Softmax output layer

Train the model and display:

Training accuracy

Validation accuracy

Training loss curve

Deliverable:

• Model architecture
• Training output
• Accuracy graph

Task 4 – Model Evaluation (6 Marks)
Evaluate the trained model using:

Confusion Matrix

Accuracy score

Sample predictions on test images

Deliverable:

• Confusion matrix visualization
• 5 test image predictions with predicted labels

Task 5 – Transfer Learning Implementation (6 Marks)
Improve your system by implementing Transfer Learning using a pretrained model such as:

ResNet50

MobileNetV2

VGG16

Steps:

Load a pretrained model

Freeze base layers

Add custom classification layers

Train the model

Compare results with your original CNN model.

Deliverable:

• Accuracy comparison between Custom CNN vs Transfer Learning model
