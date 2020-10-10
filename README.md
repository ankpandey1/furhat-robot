# furhat-robot

The goal of the project to develop a system that takes videos of different hand gestures as input, extract landmark information from them and identify the type of gesture that has been made using this information. A virtual agent will then react differently according to the given gesture.

## What are the specific objectives?

Following are the objectives of the project:
* To be able to extract landmarks
* To be able to recognise gestures with the help of extracted landmarks
* To be able to make the virtual agent(virtual salesman) react differently to each gesture

Apart from the above foundation part objectives, we also performed end to end learning where the two subsystems(extraction of landmarks and gesture recognition) will be merged into a single step.

## What does this repo contain?

The repo contains the following things:
* Subsystem 2 which is used to identify the given gesture of the annoted points on the hand using CNN. 
* End to end learning, which takes as input the video, and predicts the gesture with the help of CNN.

