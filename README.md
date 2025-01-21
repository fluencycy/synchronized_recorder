# SynchronizedRecorder
An ROS node that synchronizes and records images and kinematic data. The synchronized data pairs are saved in organized folders with timestamps as folder names. Each folder contains:
1. A synchronized image (image.png)
2. Corresponding kinematic data in JSON format (kinematics.json)

## File Structure
- Source Code: synchronized_recorder_node.cpp (main logic).
- Output Directory: recorded_data/ (generated automatically in the working directory).




