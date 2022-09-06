# CRNN for Music Genre Classification

Curricular group project - Course of Machine Learning and Deep Learning - Politecnico di Torino - 2021

Deep Learning techniques to build a 10-genres music classificator, exploiting the conversion of audio tracks in Mel-Frequency Cepstral Coefficients. Performances outstand the SVM baselines on the same dataset.

Dataset: GTZAN - Music Genre Classification. https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification, 2002.

Techniques used: data augmentation (track pitch shifting, gaussian noise addition), MFCC conversion, non-overlapping window splitting, majority voting, batch normalization, dropout, early stopping, adaptive Learning Rate.

Model used: Convolutional-Recurrent Neural Network.

Final result: 0.90 accuracy, 0.89 f1-score, perfect classification for 5 genres out of 10.
