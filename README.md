# Intel - Image Scene classification by VGG16 (Accuracy : 93%)
Goal of this project is to classify the image scene, the way i used was deep learning by Keras.</br>
Run place: Google Colab.

## Data Processing
* Combine data.
* Use "train_test_split" to split training and validation data.

## Model training
* Use Tensorflow Keras application - VGG16. (Without training weights of model)
* Open closed layers and training these layers's weights.

## Result
The accuracy of no-trained-weight model is about 91%, as for trained-weight model, it achieve about 93%.

## Reference
[Kaggle] (https://www.kaggle.com/puneet6060/intel-image-classification/notebooks)</br>
[Keras VGG16] (https://keras.io/api/applications/vgg/#vgg16-function)
