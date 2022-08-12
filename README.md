# Arctic mammal classification

Deep learning model for acoustic detection and classification of Bowhead whales. This repo contains code for the binary classification model, two classes are: Bowhead whales (BH), Other/background.

Following are some statistics about the dataset and model:
- CB-50 and CB-300 dataset for training and testing
- CB-50 contains 11138 BH annotations, CB-300 contains 5983 BH annotations
- Average duration of BH annotations: 1.78 sec
- Average low and high frequency of BH: 90.38 - 530.80 Hz
- Spectrogram window size: 3 sec
- DenseNet model

## Training data distributation
![Alt text](images/train_distribution.png?raw=true)

## Overall workflow diagram
![Alt text](images/workflow.png?raw=true)

## Results
### Training & validation performance
Following image shows the training and validation loss curves
![Alt text](images/training_loss.png?raw=true)

### Test performance
Following graph shows the performance metrices on the test annotations
![Alt text](images/test_performance.png?raw=true)