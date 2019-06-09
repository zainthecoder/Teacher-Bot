# Teacher-Bot
This is a Machine Learning Bot which will help Kindergarten student to learn about Quantity analysis and zero-number system. 

## Introduction
This project is based on base-1 number system(Unary number system). We have used '0' to represent 1, similarly "00" to represent 2 and so on. In order to represent a number N, it will ask for number of digits in N.

For example N=331, hence no of digits are 3. So first we have to give "000" ,then "000" and then finally '0' as input. This input can be in the form of video or image. Hence, the number displayed will be 331.
So, to write larger numbers, we do not need to write "0" that much times.

## Technologies used
* Python 2.7.15
* Opencv python
* Google Cloud Platform
* Google Text to Speech API

## Implementation
Firstly, We have trained 2,300 positive and 2,300 negative images of '0' using Google Cloud Computing. A Haar Cascade is basically a classifier which is used to detect the object for which it has been trained for, from the source image. So, for this project, Haar Cascade is trained for zero. On givng video of zeros through webcam, it can easily detect and count no of zeros in a frame.   

