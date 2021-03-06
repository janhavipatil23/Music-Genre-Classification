# Music-Genre-Classification

Music genre recognition algorithm using a convolutional neural network (CNN).

The algorithm split up the input songs into 3s slices. The melspectrogram of every slice is then computed, giving us input images for the CNN. 1D convolutions are used. Accuracy is around 80% at the moment.


Dataset - GTZAN Dataset (Music Folder)


Train - To train the model you can run the following command: 
python main.py -m train

This will load the audio files, format it and train the model

Test - Start with a rained model to test, put the   model and audio file in the root folder and run the following command: 
python main.py -m test -song your_song.mp3


This will load the file, process it and run it through the model. For testing on multiple song, put them all in a folder and run:
python main.py -m test -folder your_folder

Results

Accuracy of the model is 82%, however it works best with old songs (before 2000) since the dataset used to train it was created around this time. Since music has evolved, it will make more mistakes on modern songs.

