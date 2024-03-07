# Project Brief
*_Peter Cheung, version 1.0, 6 March 2024_*

This document serves as the project specification for the DVS module. The objective of this project is to challenge you to design and implement a visual-based application. You are expect to work in pairs. I recommned that you do this within the Matlab system because all the previous exercises for this module have been using Matlab.  However, you are free to choose other means such as Python with OpenCV or even C++.

The project is open-ended in the sense that you and your partner determine what you want to achieve in this project.  Given that the weighting for this project is only 25% of the entire module, I suggest that you set your goal at a level consistent with effort you require to deliver the results within the tinme available.  However, I encourage you to be as ambitious as possible without over stretching yourself.  

This project will not require you to build any hardware, although if you need to use a webcam for live data processing, one can be provided.

While you are free, and even encouraged, to define your own project, I also have a number of possible suggestions as listed below.



### Project Suggestion 1: Object Size Measurement App

Place a credit card next to any object which is either rectangular or circular in shape, take a photograph of both the object and credit card in the same frame from any reasonable angle. Automatically make the necessary geometric correct and report the dimension of the object.  The assumption is that the object is nearly flat so that depth will not be an issue.

This application is rather useful because you don't need to have any tape measure for measuring things (e.g. length of a shoe), one your credit card, a camera and this app.

### Project Suggestion 2: Vehicle number plate recognition

This is a rather obvious and very do-able project that is commonly deployed in many applications. For example, many supermarkets or motorway service stations allow free parking for, say, up to 2 hours.  There are cameras installed to recognize number plates and keep track of how long someone has parked, and working the appropriate parking charge.

This project is to turn a number plate image into registration number.  There are plenty of open-source dataset available.  Here are just a few:
.....

### Project Suggestion 3: Brain Tumor Detection

Image processing is now used routinely to help physicians to perform diagnosis.  [Here](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=download) is a link to a set of open source dataset containing MRI images of brain with tumor.  The challenge is to detect and report the location and size of the tumor.

### Project Suggestion 4: "Artify" photographs

The idea is to turn a photograph of a scene or a person, and process it to create something that looks more like it being painted as an artwork, and not a photo.

## Datasets

The project you decide upon may need datasets not mentioned above. There are many sources in the public domain.  For example, here is the [Grappa Project list of data](https://grappaproject.eu/databases/open_datasets/).  [Here](https://www.pexels.com) is repository of free photos.  [Here](http://www.cbsr.ia.ac.cn/english/Palmprint%20Databases.asp) is another source for biometrics dataset from China.

##  Deliverables

You and your partner are expected to submit the results from this project via a combined GitHub repository.  The deadline is 4.00pm on Friday 22 March.  

In this repository, you must provide:
1.  A short team report as the README.md file in the Github repo main folder explaining what you and your partner have achieved. 
2.  Each member provide a person statement declaring what you personally have contributed to the project, a reflection section on what you have learned, reasons for your design decisions, mistakes you have made and what you would do differently if you were to do this again.
3.  A folder that contains all the code that your team has developed to implement the application, and a README.md file in this folder that provide evidence that your application is working.

##  Assessment Criteria

This work will be assessed on your competency in processing and handling visual data, the level of difficulties in the task(s) you have chosen to solve and the extend that you have achieve the goals that you have set out.   To get the top grade, you need to surprise me!