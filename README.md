# Video_Classification
The repository builds a two approaches for video classification (or action recognition) using UCF50 using TensorFlow. To propagate a video through a model, we randomly select a specific number of frames from it. Below are two neural nets models:
Human_action_recognition using ConvLSTM and Pose Detection using MediaPipe.

For pose estimation we will use media pipe library that will mark feature points in our body(landmark coordinates). Which will be further used for our recurrent neural network for classification.  
Fot ConvLSTM we extracted relevant features from a video frame which was in image form. That was later sent through RNN 
