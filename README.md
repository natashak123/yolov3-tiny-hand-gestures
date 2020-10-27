# yolov3-tiny-hand-gestures
Hand gestures detection using yolov3 tiny model for a news application

Dataset

The dataset comprises images of 2 gestures namely Resume, and Stop. Resume gesture is used to resume the reading of the news, and Stop gesture is used to stop the reading of the news. A total of 1500 images are used for training the model.

Training

Training of the yolov3-tiny model was done on google colab.

Since our news application is ios based, the model was first converted to keras format and then later on converted to coreml format.
