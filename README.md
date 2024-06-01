

# Project: Image Classification Using Pre-Trained MobileNetV2 Model


1. Implemented an image classification pipeline using TensorFlow and Keras to classify images into three categories: bicycles, bottles, and cars.
2. Utilized Google Colab for the development environment and accessed data stored on Google Drive.
3. Developed a custom data loader to load and preprocess images from the dataset. The images were resized to 100x100 pixels and the data was split into training, validation, and testing sets.
4. Applied data augmentation techniques such as resizing, scaling, flipping, rotating, shifting, and zooming using TensorFlow’s ImageDataGenerator to increase the diversity of the training data and improve the model’s ability to generalize.
5. Fine-tuned a pre-trained MobileNetV2 model with a custom top layer to classify the images. The MobileNetV2 model was chosen due to its balance between accuracy and efficiency, making it suitable for real-time applications.
6. Trained the model for 15 epochs and achieved a training accuracy of 99.2%, a validation accuracy of 96.67%, and a testing accuracy of 100%.
Defined a function to visualize the correctly and incorrectly classified images, providing insights into the model’s performance.
