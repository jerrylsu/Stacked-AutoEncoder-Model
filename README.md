## Novel Molecular Toxicity Prediction Model

Novel molecular toxicity prediction model based on Softmax / Deep Neural Network / Stacked Autoencoder / Stacked Capsule Model.

| Model Name | Recall | Precision  | F1 | AUC | Accuracy |
| :----: | :----: | :----: | :----: | :----: | :----: |
| Softmax Model | 0.7235 | 0.8601 | 0.7859 | 0.8100 | 0.8154 |
| DNN+Softmax Model | 0.7765 | 0.8354 | 0.8049 | 0.8209| 0.8237 |
| SAE+Softmax Model | 0.7706 | 0.8562 | 0.8111 | 0.8283 | 0.8320 |
| SAE+CapsNets Model | 0.7353 | 0.8621 | 0.7937 | 0.8158 | 0.8209 |

### 1. Softmax Model

- loss

![loss](./data/results/softmax/loss.png)

- validationset classification

![validationset](./data/results/softmax/validation_best.png)

### 2. DNN+Softmax Model

- loss

![loss](./data/results/deep_neural_network/loss.jpeg)

- trainset classification

![tainset](./data/results/deep_neural_network/train_epoch4.png)

- validationset classification

![validationset](./data/results/deep_neural_network/validation_best.png)

### 3. SAE+Softmax Model

- loss

![loss](./data/results/stacked_autoencoder/loss.png)

- validationset classification

![validationset](./data/results/stacked_autoencoder/validation_best.png)

### 4. SAE+CapsNets Model

### Reference

- Sara Sabour, Nicholas Frosst, and Geoffrey E. Hinton. Dynamic routing between capsules. In NIPS, pages 3859-3869, 2017.

- [Capsule Networks Explained](https://kndrck.co/posts/capsule_networks_explained/?nsukey=T%2FHdvRcjUBfihkYW23QZW0A8Q%2BljC4XZ9xJ0fVl2CVMEplz%2F1PwPluHYtS%2FUUxitMi%2BroERqd7kohaw8wXNUYmJUzpRpzSz6sud35oxMViGrNEpilQ7i3%2BPynLRiLYP6IEd7tmfNSkYGb%2F2vn4J4pnIht3tu6lihLD6vwQ7frfIQvDI8G3K0f1ILzbiFWx%2FV4%2BYufwFyWlyf9ypf7TDd1g%3D%3D)

- Wang, Y.-W., Huang, L., Jiang, S.-W., Li, K., Zou, J., & Yang, S.-Y. (2020). CapsCarcino: A novel sparse data deep learning tool for predicting carcinogens. Food and Chemical Toxicology, 135, 110921.

- [http://www.jerrylsu.net/articles/2021/ml-Capsule-Networks.html](http://www.jerrylsu.net/articles/2021/ml-Capsule-Networks.html)