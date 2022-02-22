# Live Color-Detection
Thse project detect blue color in a live frame using hsv colorspace method

# Requirements
* Python3
* Python Libraries: `numpy`, `cv2`
* Anaconda environment

# Explanation

1. These project capture the live frame using the specified camera index
2. Then you have read the frames and then convert the frames into HSV (Hue, Separation, Value)
3. You have create the mask of the blue color that you want to extract from the live video by giving high and low range values.
4. Finally you have to perform `bitwise-and` operation on the frame and the mask.
5. Display the video

