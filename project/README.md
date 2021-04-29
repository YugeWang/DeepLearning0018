
# Description
My project mainly used Edge Impulse, you can view it via https://studio.edgeimpulse.com/public/21959/latest. 

Here are few descriptions of files uploaded.

Instructions of connection of Arduino Nano 33 BLE Sense to the project can be found at https://docs.edgeimpulse.com/docs/arduino-nano-33-ble-sense. 


## 1. Traning and testing dataset used in this project. 
Here is the Python code to view audio datasets:

import numpy as np

training = np.load("ei-light_audio_recognition-mfcc-x.npy")

testing = np.load("ei-light_audio_recognition-mfcc-y.npy")

print(training)

print(testing)

## 2. Document for running the model locally on the terminal.
This documnet was exported directly from my project on Edge Impulse, to run it, open 'flash_mac.command', after the process is done, then type '$ edge-impulse-run-impulse'. 

## 3.Slides used in presentation in the week 10. 
