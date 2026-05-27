IMP: "MAKE SURE TO USE *PYTHON v3.11* else mediapipe would cause error"

This is a pose estimation/detection system.

The folder "Pose" consists of video which is being used in the code.

Make sure to keep the module file in the same folder in which the code is being used.

This module tracks the right elbow of the person in the video you can change the tracking point by just editing the particular field:
print(lmList[14]) <----- Here change the number in the lmList according to your need.
             cv2.circle(img, (lmList[14][1], lmList[14][2]), 10, (0, 0, 255), cv2.FILLED) <----- Here change the numbers in the lmList accordingly.
             
Run the code and get the result.
