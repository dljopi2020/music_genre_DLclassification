# music_genre_DLclassification
 In this repository music genre classification systems (i.e., CNN; RNN) are implemented to classify music genres based on audio fragments of songs in a WAV format. The fragments are based on whole songs found in the GTZAN dataset. Additionally, we augment our data-set by dividing the fragments in subsets in order to improve the training step in our models.
 
You can run this project, which is an iPython notebook file (.ipynb), in a Jupiter notebook, or as we did: online in Google Collaboratory. Here you can run the different cells from top to bottom in order to run the full experiment.
 
Simply run the code. Firstly, the data will be loaded from our Google drive and subsequently prepared according to fragment sizes of 5, 10, 15 and 30 seconds. Secondly, the CNN and RNN (i.e. LSTM) will be set-up. Thirdly, the models will be trained. Fourthly, the models are implemented for the test data-set. Fiftly, results are plotted.

Note, in the main loop (at In [14]), you can select which model (CNN or LSTM) you wish to run by setting the parameter 'model_type' to 'cnn' or 'lstm' respectively.
