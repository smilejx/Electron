# Electron
This is the GitHub repo for Electron, a delivery robot. The goal of the robot is to succefully be able to deliver items to cubicles in an office building be it office supplies or food. The robot must be able to autonomously drive around a building while successfully retrieving and delivering these items, constantly.

# Navigation on Turtlebot

# Making your delivery bot more aware
Because we want our robot to be smarter, you want the robot to know when an object is placed or taken off of it and what the object is, so that it can act accordingly. ItemNet is a neural network trained on NVIDIA DIGITS with the Caffe framework on high-end NVIDIA GPUs. It has the ability to classify various classes of objects you find in an office space. We were able to learn how to do this from the ground up by following Dusty's tutorial on Jetson Inference.
https://github.com/dusty-nv/jetson-inference

# User Interface
