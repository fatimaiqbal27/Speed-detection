# Speed-detection
Our project has 3 modules: 
Module 1: Traffic Light Control 

Computer vision can be used for traffic violation control by analyzing video footage of vehicles 
to detect when they are breaking traffic laws. For example, computer vision algorithms can be 
used to detect when a vehicle is running a red light, speeding, or making an illegal turn. This can 
be done by training a machine learning model to recognize these types of violations in video 
footage and then using that model to analyze video feeds from traffic cameras or other sources. 

Design details: 

A camera will be used detect the number the cars in each lane on a road going towards the 
intersection. After receiving image form camera (as shown above), we will go into the processing 
stage where we will use OpenCV to calculate the number of cars in each lane at the intersection 
in real time.

This data will then be fed through a Probabilistic Algorithm which will then decide which signal 
to give. Our module was able to count the number vehicles passing through each lane and change 
the traffic lights changing time accordingly and detect any traffic violations. 
