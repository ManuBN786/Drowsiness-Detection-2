# Drowsiness-Detection-2
Matlab Code for Drowsiness Detection 2

A Matlab code is written to moniter the status of a person and sound an alarm in case of drowsiness. i have already trained the SVM classifier with Fatigue and Non Fatigue samples.

How to run??

    Unzip and place the 'Sleep' folder in the path of Matlab.
    Turn on your webcam, go to command window and type 'imaqtool' to find the supported adaptors.
    Open main.m and go to line no. 17 and change the adaptor name to the supported one. (Usually 'winvideo',1 is supported in all windows versions).
    Now run main.m
    Place yourself at a distance such that your face is visible in the window
    Non Fatigue Status: The default status, appears when your eyes are wide open and mouth is closed
    Fatigue Status: When eyes are closed and mouth is opened for several seconds, the alarm sounds a beep.
    Make sure the room is well lit Note: The model is not trained to work perfectly under dark or very low dim light conditions, I will upload a much better code once I get better results with an efficient set of features.

Cite the following if you are using my work:

[1] Manu, B. N. "Facial features monitoring for real time drowsiness detection." Innovations in Information Technology (IIT), 2016 12th International Conference on. IEEE, 2016.

IEEE Paper Download link: https://www.researchgate.net/publication/315685957_Facial_Features_Monitoring_for_Real_Time_Drowsiness_Detection

PPT Download link: https://www.researchgate.net/publication/315686000_Facial_Features_Monitoring_for_Real_Time_Drowsiness_Detection_PPT

Suggestions and comments are always welcome,

Thanks in advance,

Manu B.N
