# Human_Pose_Detection_Keypoints_R-CNN
Human Pose Detection

- Human pose detection is detecting the important keypoints that can describe the orientation or movement of a person. You can also relate it to facial keypoint detection where we detect the interesting parts of a face and mark them.


- R-CNN, or Region-based Convolutional Neural Network, is an object detection model that uses a deep learning approach to identify and classify objects in images by first generating "region proposals" and then running a CNN on each proposal.

- Keypoints R-CNN are the keypoints on 17 human parts and body joints.
They are: ‘nose’, ‘left_eye’, ‘right_eye’, ‘left_ear’, ‘right_ear’, ‘left_shoulder’, ‘right_shoulder’, ‘left_elbow’, ‘right_elbow’, ‘left_wrist’, ‘right_wrist’, ‘left_hip’, ‘right_hip’, ‘left_knee’, ‘right_knee’, ‘left_ankle’, ‘right_ankle’.

- We are using a pre-trained Keypoint RCNN model with ResNet50 base which has been trained on the COCO keypoint dataset for the projec today.
