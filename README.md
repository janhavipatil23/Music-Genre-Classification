# Music-Genre-Classification

Music genre recognition algorithm using a convolutional neural network (CNN).

The algorithm split up the input songs into 3s slices. The melspectrogram of every slice is then computed, giving us input images for the CNN. 1D convolutions are used.

Accuracy is around 80% at the moment

Dataset

Download the GTZAN dataset here and extract it in a musics folder.

You can also get already formatted data for the CNN and the trained model here, and simply extract the files.
