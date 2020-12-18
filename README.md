# Computer Vision For Crowd Detection
***
Detection and monitoring of crowds using computer vision has applications in crowd management and surveillance. Crowd management is important for public safety, especially now amidst the COVID-19 pandemic. Computer vision algorithms can assist with social distancing efforts aimed at slowing the spread of the virus, and alert when violations on the permitted headcount within a space occur. Crowd counting and localization can also be useful when designing public spaces such as airports and malls, and in making decisions on how to manage crowds in these public spaces.

###  Team Members
 - Tasneem Naheyan
 - Kenan Li
 - Inder Dhillon
 - Jing Li
 - Sadman Sakib
 - Reza Karimi
 - Youssef Guirguis

### Data
We used the WILDTRACK dataset for this project.

### Repo Structure
Different components of the project are divided into seperate branches:
1. wildtrack_dataset contains the homography transformation and distance calulation functions.
2. YOLO branch contains the YOLOv3 model code.
3. evaluation branch contains the code to run the evaluation metrics. Pre-generated YOLO detections provided in .pkl files.
4. Kernel_Density_Estimation contains the KDE code.
5. main branch contains the script to generate location position predictions and saves them to .pkl files.
