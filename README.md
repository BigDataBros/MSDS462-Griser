An Android application to identify mushrooms/fungi from a phone/device's camera
June 2022

The model was trained off of the existing model EfficientNet Lite #0 (https://tfhub.dev/tensorflow/efficientnet/lite0/classification/2.)
which was pre-trained on the ImageNet 2012 dataset dataset (ILSVRC-2012-CLS).

The application's model was trained on a small subset of the ImageNet 21K dataset:
9053 randomly selected images already identified as part of 72 classes of various types of mushrooms and fungy
The final model had an accuracy of 73.55% and a loss of 1.634

The application uses the device's camera and will give an instantaneous classification of the image.
The application displays the classification, confidence score, scientific name, and then editibility.
The application also changes the color of the text of the classification label based on edibility,
e.g. an edible fungus is presented in green font and a poisonous fungus is presented in a red font.
