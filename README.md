# ML Classification
Implementation of Resnet-RS for training, validation and testing

The Resnet-RS models from: https://github.com/nachiket273/pytorch_resnet_rs 

### Dataset Folders organization:

![folder_organization](./files/Folder_division.PNG?raw=true "Dataset Folders Organization")

### How to use:

* In the "Initial configuration" part, replace the ImageFolder path with the path of your own custom dataset
* There you can also alter the number of epochs, batch size, k-folds of your preference

### Values used for this program:
#### (Those same values were used both for binary and multiclass classification)

* **Number of folds (k)**: 10
* **Batch size**: 51
* **Dropout rate**: 0.25
* **Loss function**: CrossEntropyLoss()

#### Pre-trained Network:
* **Number of epochs**: 20

#### NOT pre-trained Network:
* **Number of epochs**: 200
