# Game of Deep Learning Hackathon (Analytics Vidhya)

## Problem Statement
Ship or vessel detection has a wide range of applications, in the areas of maritime safety,  fisheries management, marine pollution, defence and maritime security, protection from 
piracy, illegal migration, etc. Keeping this in mind, a Governmental Maritime and Coastguard Agency is planning to deploy a computer vision based automated system to identify ship 
type only from the images taken by the survey boats. You have been hired as a consultant to build an efficient model for this project.

There are 5 classes of ships to be detected which are as follows:

{'Cargo': 1, 
'Military': 2, 
'Carrier': 3, 
'Cruise': 4, 
'Tankers': 5}


## My Approach

- I have used fastai for this image classification hackathon.

- Used resnet50 model for tansfer learning.Improve the model. 

- First created model for pixel size 128 and then with size 256.

- Used data augmentation (rotations, ,zoom, lighting, warping etc).

- Freeze and Unfreee model for 15 epochs.
