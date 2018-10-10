# CINIC-10-TFLoader

This repository contains a data loader of "[CINIC-10](https://github.com/BayesWatch/cinic-10)" dataset for TensorFlow. A training case using TFLearn is given in `residual_network_cinic10.py`.

CINIC-10 data can be loaded with the line below:
```
XTrain, YTrain, XVal, YVal, XTest, YTest = cinic10.loadData("/path/to/dataset/folder", oneHot=True)
```

`loadData()` method returns 6 numpy arrays respectively: Training set images, training set labels, validation set images, validation set labels, testing set images, testing set labels.

This script also downloads and extracts dataset files if dataset is not in the specified folder.

You can check `residual_network_cinic10.py` file for an example.


## License
The source code is licensed under [MIT License](./LICENSE).
