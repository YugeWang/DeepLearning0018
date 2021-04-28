# Deep Learning CASA0018

Python code to view audio datasets:

import numpy as np

training = np.load("ei-light_audio_recognition-mfcc-x.npy")

testing = np.load("ei-light_audio_recognition-mfcc-y.npy")

print(training)

print(testing)
