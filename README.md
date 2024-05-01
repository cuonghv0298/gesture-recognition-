# Gesture Recognition Assignment
This is our assignment for upgrad's course


## Agenda
* [Problem statement](#problem-statement)
* [Dataset](#approach-methods)
* [Structure](#structure)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## Problem statement
Recognising 5 different hand gestures to control a smart TV

We need to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
 - Thumbs up:  Increase the volume
 - Thumbs down: Decrease the volume
 - Left swipe: 'Jump' backwards 10 seconds
 - Right swipe: 'Jump' forward 10 seconds  
 - Stop: Pause the movie
 
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

## Dataset
You can download the dataset [here](https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL)

This dataset contains a 'train' and a 'val' folder with two CSV files for the two folders. These folders are in turn divided into subfolders where each subfolder represents a video of a particular gesture. Each subfolder, i.e. a video, contains 30 frames (or images). Note that all images in a particular video subfolder have the same dimensions but different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160 (depending on the webcam used to record the videos). Hence, you will need to do some pre-processing to standardise the videos. 

 

Each row of the CSV file represents one video and contains three main pieces of information - the name of the subfolder containing the 30 images of the video, the name of the gesture and the numeric label (between 0-4) of the video.

## Structure
* convLSTM2D(final_model).ipynb is our notebook code all experiments. 
* README.md 
* requirements.txt 
* TODO.md : how we work together
* imgs folder contains the evaluation rubric image
* models folder contains the json to load the result training
(You can download all our trained models at this [link](https://drive.google.com/drive/folders/1tZJGqxkOiC6DFbNHU5S6EqA8Kw5dzZW3?usp=drive_link))

## Acknowledgements
1. https://realpython.com/introduction-to-python-generators/
2. https://www.youtube.com/watch?v=bD05uGo_sVI

## Contact
Created by [Huynh Viet Cuong](https://cuonghv0298.github.io/) - feel free to contact me!
