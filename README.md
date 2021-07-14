# BT-prediction-model-pytorch-

We attach a simple code that trains and evaluates an Acral Lentiginous Melanomas BT (breslow thickness) prediction CNN model on dermoscopy images. class

In the case of the classification model, in the case of the data type, the path of the folder in which the data in the general image format is divided by class is written in the code. For example, If the folder name of the training dataset is 'BT_train' and it is composed of 'BT under 0mm' folder and 'BT over 0mm' folder, write train_dataset folder path = 'xxx/xxx/BT_train' in the code.

In the case of a regression model, you must prepare a json file containing the path and BT value of the images for each dataset .
