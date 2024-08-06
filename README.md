# Mindrive-EEG-Controlled-Wheelchair

## Project Overview
The project aims to create an EEG-controlled wheelchair system for individuals with severe physical disabilities, enabling control through brain signals rather than traditional joysticks or switches. By processing alpha waves (7-13Hz) from EEG signals, the system translates user intentions into directional commands (forward, backward, left, right) and stop commands. The focus is on minimizing the number of EEG channels to reduce costs. Machine learning and deep learning techniques will classify these signals, while real-time object detection via a Pi camera will enhance navigation and safety. This intuitive system aims to provide a cost-effective, user-friendly solution for enhanced mobility.

## Need Analysis
With a rising global need for assistive technology, traditional wheelchairs offer limited control for those with severe impairments. EEG-controlled wheelchairs, utilizing real-time object detection and advanced BCI technology, promise improved navigation and safety. Incorporating machine learning for signal processing and iterative user feedback will enhance functionality and user experience, addressing challenges faced by individuals with motor impairments.

## Methodology

![mm](https://github.com/user-attachments/assets/fc8b3750-8fc2-4e8a-9132-3bb8ed8cb27d)

## System Components
1. Signal Preprocessing using MATLAB: This removes artifacts and noise from 
the EEG signals.
2. Feature Extraction using MATLAB: This extracts relevant features from the 
EEG signals that can be used to control the wheelchair.
3. Machine Learning Classifier: This is used for classification of EEG signals. We 
plan to use different ML/DL techniques and compare them. The classifier 
translates the extracted features into control commands for the wheelchair (e.g., 
move forward, turn left).
4. Control Unit: This unit receives the control commands from the classifier and 
translates them into signals that the wheelchair understands.
5. Wheelchair: This executes the commands received from the control unit. There 
may be additional safety features included here like obstacle avoidance sensors.
6. Pi camera: This is used for capturing live video which would be used to detect 
obstacle.
