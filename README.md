## Traffic Vision

A Deep Learning Project for Traffic Sign Recognition using CNN, Tensorflow and Keras - Achieves 94.8% accuracy

## Architecture

- Conv2D layer (filter=32, kernel_size=(5,5), activation=”relu”)
- MaxPool2D layer ( pool_size=(2,2))
- Dropout layer (rate=0.25)
- 2 Conv2D layer (filter=64, kernel_size=(3,3), activation=”relu”)
- MaxPool2D layer ( pool_size=(2,2))
- Dropout layer (rate=0.25)
- Flatten layer to squeeze the layers into 1 dimension
- Dense Fully connected layer (256 nodes, activation=”relu”)
- Dropout layer (rate=0.5)
- Dense layer (43 nodes, activation=”softmax”)

## Metrics

![Accuracy Chart](https://github.com/ashtan19/TrafficVision/blob/master/public/AccuracyChart.png)
![Loss Chart](https://github.com/ashtan19/TrafficVision/blob/master/public/LossChart.png)
