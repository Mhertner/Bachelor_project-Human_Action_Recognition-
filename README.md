# Visionbased Human Motion Analysis In Gymnastics

This repository contains code for the paper 'Vision Based Human Motion Analysis In Gymnastics' written by Sofus Konglevoll, Morten Holck and Gustav Bakhauge. 

The project consists of two parts: collecting and creating a data set and classifying sub-actions within these videos.

The data set consists of ~200 videos of homemade gymnastics videos labelled frame by frame with one of four labels: Idle, Take-off, Skill or Landing. Furthermore, from these videos we extracted a skeleton, which was used for the classification of sub-tasks. If you are interested in the data you can write me at mert@itu.dk
To do the classification part we compared two models a CNN and a bi-LSTM - The code for these models are in the folder called 'models' in src.

This is the repository we worked in, so it is a bit messy.
