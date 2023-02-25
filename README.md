# Real-Time-Hand-Tracking-Using-Posenet
MediaPipe Hands utilizes an ML pipeline consisting of multiple models working together: A palm detection model that operates on the full image and returns an oriented hand bounding box. A hand landmark model that operates on the cropped image region defined by the palm detector and returns high-fidelity 3D hand keypoints. This strategy is similar to that employed in our MediaPipe Face Mesh solution, which uses a face detector together with a face landmark model.

![image](https://user-images.githubusercontent.com/112906488/221363064-d864cbb6-3050-492f-b3fd-a33f54374880.png)

![image](https://user-images.githubusercontent.com/112906488/221363399-6e291b8b-3ffa-4e21-b5ac-a9bf924a5741.png)
# Workflow

- Install MediaPipe
- Create Object from Class Hand
- Detecting Landmarks and Draw points on Hand
- Extracting Values of each landmark
- Highlight Fingertips

# Project Demo

https://user-images.githubusercontent.com/112906488/221363204-2fdd6cae-d820-4b82-ad81-ecba4a7517bb.mp4


