# Music-Genre-classifier

The Music Genre Classifier is a project used to classify a song based on the 
genre. The Music genre Classifier is an implementation of Deep learning 
concepts to automatically classify different musical genres from audio files.
The audio files are classified based on their low-level features of frequency 
and time domain.

In this project, we have used a dataset of audio tracks having similar size 
and similar frequency range. So, GTZAN genre classification dataset is the 
most apt as it was collected for the same purpose. The GTZAN genre 
collection dataset was collected in 2000-2001. Consisting of 1000 audio files 
each having 30 sec duration, classified into 10 genres with each containing 
100 tracks in .wav format. The genres are Blues, Classical, Country, Disco, 
HipHop, Jazz, Metal, Pop, Reggae and Rock.

We have used K-nearest neighbours algorithm for this project as in various 
researches this algorithm has shown the best results for this problem. 
KNearest Neighbours is a popular machine learning algorithm for regression 
and classification. It makes predictions on data points based on their 
similarity measures i.e distance between them.

For Feature Extraction, we have used the concept of Mel Frequency
Cepstral Coefficients which is the most widely used feature extraction 
method for automatic speech recognition systems.
The classifier is approximately 70 percent accurate. Which is on the higher 
spectrum compared to other classifiers considering that Music in itself can 
have many mis clippings and distortion while recording.


#steps to follow
step1 - Run the cells individually from the file music_genre.ipynb .
step2 - A dumpfile mydataset.dat is created when we run all the cells .
step3 - Open the file music_genre.py and mention the path of the music file with .wav extension in the respective position.
step4 - Now open the terminal and run music_genre.py file using the command python3 music_genre.py to get the output.


Required libraries : 
!pip install python_speech_features
!pip install scipy
