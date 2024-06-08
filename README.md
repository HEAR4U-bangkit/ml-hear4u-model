# Machine Learning Path Repository

This repository used for sound preprocessing and creating model for Hear4U app. We make 2 models for this classification sound, using CNN Architecture and pre-trained YAMNet Architecture. In the end, we are using pre-trained YAMNet Architecture to develop the sound detection system, achieving 94% accuracy and 83% validation accuracy.

## Dataset

Hear4U dataset is a labeled collection of 1,000 environmental audio recordings. The dataset consists of 10 classes, with 100 examples per class. This audio data will be used to detect sound around us.

- Crying Baby
- Car Horn
- Cat
- Dog
- Door Knock
- Door Bells
- Glass Breaking
- Gun Shot
- Siren
- Train

We gathered and combined the audio file from [ESC-50 Dataset](https://github.com/karolpiczak/ESC-50) and [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html)

## Workflow

Data Collecting ➡️ Sound Preprocessing ➡️ Creating Model ➡️ Deploy to Cloud

## Model

### Using CNN Architecture

![cnn_acc](https://github.com/HEAR4U-bangkit/ml-hear4u-model/tree/main/archived_model/cnn_acc.png)

### Using Pre-trained YAMNet Architecture

![yamnet_acc](https://github.com/HEAR4U-bangkit/ml-hear4u-model/tree/main/archived_model/yamnet_acc.png)

## References

[Simple Audio Recognition](https://www.tensorflow.org/tutorials/audio/simple_audio)
[Transfer learning with YAMNet for environmental sound classification](https://www.tensorflow.org/tutorials/audio/transfer_learning_audio)
