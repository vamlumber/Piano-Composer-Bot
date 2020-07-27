<<<<<<< HEAD
# Classical Piano Composer

This project allows you to train a neural network to generate midi music files that make use of a single instrument

## Requirements

* Python 3.x
* Installing the following packages using pip:
	* Music21
	* Keras
	* Tensorflow
	* h5py

## Training

To train the network you run **lstm.py**.

E.g.

```
python lstm.py
```

The network will use every midi file in ./midi_songs to train the network. The midi files should only contain a single instrument to get the most out of the training.

**NOTE**: You can stop the process at any point in time and the weights from the latest completed epoch will be available for text generation purposes.

## Generating music

Once you have trained the network you can generate text using **predict.py**

E.g.

```
python predict.py
```

You can run the prediction file right away using the **weights.hdf5** file
=======
# Piano-Composer-Bot
LSTM RNN

To run use python lstm.py

and then use predict.py to run
>>>>>>> 1ba2228d90c8b33effb77c2fac3881e747ef6065
