# Hands-On Project: Real-time Hand Gesture Recognition for Sign Language

### Introduction to The Project
Majority of deaf-and-mute people use sign language produced by body actions such as hand gestures, body motion, eyes and facial expressions to communicate amongst each other and with non-impaired people in their daily life. However, it has become a barrier for mute and deaf communities which intend to integrate into society. Therefore, it is significant to have a medium that can recognize and translate gesture into understandable words by common people, as the information carried by hand gestures is always principal in sign language. To bridge the communication gap, a hand gesture recognition system for Sign Language Recognition (SLR) is required.

<div align=center><img src=https://github.com/JianqiaoMao/UCL_AISOC_Tutorial_HandGestureRecognition/blob/main/IMAGES/ASL.png width=900 /></div>

This project aims to design a real-time vision-based hand gesture recognition system with machine learning techniques, which potentially makes deaf-and-mute people life easier. In practice, signs are always continuously spelled words mixing both dynamic and static gestures, so the wanted recognition system should be able to recognize both dynamic and static gestures in ASL with a promising accuracy.

<div align=center><img src=https://github.com/JianqiaoMao/UCL_AISOC_Tutorial_HandGestureRecognition/blob/main/IMAGES/system_diagram.png width=500 /></div>
 
### Aim
At the end of this session, you will be able to:
•	Understand basic image processing techniques and their implementation
•	Get familiar with advantages and disadvantages of a set of machine learning models
•	Have practical experience in conducting an individual project
•	Know how to apply the state-of-the-art techniques in your own work.
### Outline
Typically, a real-time SLR systems follow a common framework and process, i.e. data acquisition, pre-processing, feature extraction and classification
 
 <div align=center><img src=https://github.com/JianqiaoMao/UCL_AISOC_Tutorial_HandGestureRecognition/blob/main/IMAGES/process.png width=900 /></div>
 
This notebook is formulated as a baseline framework in non-real-time training and testing, and you are encouraged to:
1) Modify to improve any applied technique in any stage, e.g. preprocessing, feature extraction, classification. 
2) Propose your own implementations to replace the original technique, which might lead to an amazing improvement.
3) Assemble elements into a real-time recognition system and play with it.

### Environment Requirements

It is recommended that you run this project in a virtual environment. A good virtual
environment manager is Anaconda: https://anaconda.org/
Python 3.6 is a must-have to conduct this project.

In your Python 3.6 environment or machine, from the route directory of where you
cloned this project, install the required packages by running::

    $ python -m pip install -r requirements.txt
