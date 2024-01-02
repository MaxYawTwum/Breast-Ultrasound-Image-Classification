Breast Ultrasound Image Classification is a very essential field that has gained interest of researchers. 

Recognizing crucial characteristics within ultrasound images associated with breast cancer is essential for potentially saving lives in the future.

In this project, I utilized a Deep Learning model (CNN) to help identify the best strategies for deep learning-based BUS classification.

**    SUMMARY OF THE MODEL
    The Model is a convolutional neural network (CNN) architecture that has three convolutional layers.

    It takes input images with dimensions of 128x128 pixels.

    The Convolutional layers have 16, 32, and 16 filters respectively, followed by max-pooling layers.

    Dropout layers are applied after each convolutional layer to reduce overfitting.

    The output of the last max-pooling layer is then flattened and passed through two dense (fully connected) layers with 128 and 1 neurons respectively.

    It outputs a single value which is either a 0 or 1 signifying Benign or Malignant respectively.

    The model was trained over 20 epochs with 411,377 parameters
