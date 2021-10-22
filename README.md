# MotionDetector
Problem statement is - To show a dataframe using pandas which shows time intervals in which motion of a object was there and been captured by Computer's camera and at what time interval there was no motion . 

Steps Being followed-:-
1. To use videoCapture() method
2. to convert the frame to a gray image
3. to convert the frame to a gaussian image for increasing the efficiency of the gray image
4. to calculate the threshold and dilate the foreground object
5. Once dilation is done , capture the contours
6. to make a rectangle with help of contours
7. to show all this in specific windows and use key 'q' to destroy the windows and to stop computer from capturing the video
(=> 1 window will show gaussian video , 1 window will show normal colored video with a rectangle around it , 1 window will show threshold based video)

=>In order to show time intervals , make a list 'times' and append status into it and convert the list 'times' into required dataframe
