
# Description
My project mainly used Edge Impulse, you can view it via https://studio.edgeimpulse.com/public/21959/latest. 

## 1.  Report of the whole project. 
This report contains more detailed description of the project. Including application flowchart, data description, and modifications made.
I did not directly used the markdown templet as I want to import some tables and graphs

## 2. Traning and testing dataset used in this project. 
Here is the Python code to view audio datasets:

import numpy as np

training = np.load("ei-light_audio_recognition-mfcc-x.npy")

testing = np.load("ei-light_audio_recognition-mfcc-y.npy")

print(training)

print(testing)

## 3. Document for running the model locally on the terminal.
This documnet was exported directly from my project on Edge Impulse, to run it, open 'flash_mac.command', after the process is done, then type '$ edge-impulse-run-impulse'. 

## 4.Slides used in presentation in the week 10. 
