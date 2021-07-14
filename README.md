# Deepfake-Detection

Deepfakes are synthetic media in which person in an existing image or video is replaced with someone else’s likeness.

It leverages powerful techniques from Machine Learning and Artificial Intelligence to manipulate or generate visual and audio content with a high degree of potential to deceive the viewers.

PROPOSED SYSTEM

Using a dataset of videos from different dataset sources like Kaggle.

Video is fed into one of the two Image feature extraction networks.

The output of these is fed into a small Long Short term Memory network (LSTM). It is used to process the frames in a sequential manner so that analysis of the video can be made by comparing frame at ‘t’ second with frame of ‘t-n’ seconds.
This is then connected to a classification later, outputting either “0” for manipulated video or “1” for pure video.


