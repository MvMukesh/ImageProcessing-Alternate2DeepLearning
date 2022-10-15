# ImageProcessingCounter-Alternate2DeepLearning
When not to bother about Deep Learning techniques and Consider Image Processing


## Problem Statement:
Count all Parking Spaces present in almost any parking location

## Data at Hand
1. Related Images and Videos

## Assumptions 
Assuming camera will not move more than `0.03490659-radians` in future

## AIM
1. Make it pocket friendly,  and very adoptable

## Problem Seen
1. It is really, really hard in a commercial lot to find power and electricity in optimal locations to power occupancy cameras
2. Cost of mounting a new pole in correct spot usually takes solution out of range of adoption for commercial parking operators

## What I am not using?
1. Not using `SSD or Yolo` to detect Cars, using these models will increase cost of implementation and other related complexity 
2. Learning : `We dont need always complicated techniques to solve such problem`  
3. Not using contour method to find lines automatically in image

## What I am using/doing?
**`I am using Simple Image Processing techniques to find out if the car is present in parking section or not`**

1. In images I am marking parking spaces manually as my reason of interest, `Why not using a loop?`
  
2. this can be done using a `for loop`, but in given usecase image is being take from a particular angle so parking space lines are not of same length i.e. Image is not a perfect Birf Eye View
3. Between parking space some section are not exacly for parking,they are being used for collecting trolly and other stuff
4. Built outline of parking space is not same for each section
5. section 1 and 2 are same but, in section 2 there is a trolly collection section
6. section 3 have some inlet and outlet for cars
7. section 3 also have a solid pavement in it, which cannot be seen in other 2 section

## Plan of Action
1. Do some code to Select and Deselect these parking spaces using CV2, arrange data in a list to use within the main code 
2. Prepare a supporter module which will help in executing step:1
3. Make a main file and execute full code here



  
  
