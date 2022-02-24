# Music-Genre-Classification

Music genre recognition algorithm using a convolutional neural network (CNN).

The algorithm split up the input songs into 3s slices. The melspectrogram of every slice is then computed, giving us input images for the CNN. 1D convolutions are used. Accuracy is around 80% at the moment.


Dataset - GTZAN Dataset (Music Folder)


Train - To train the model you can run the following command: python main.py -m train

This will load the audio files, format it and train the model
