# Civil6451final
Photogrammetry course final project

Requirement:
•	Request: 
Use the stereo Kitti Benchmark odometry image data. 
•	Steps to implement:
1.	Use to calibration data to generate rectified images. 
2.	At time t, perform interest point extraction and matching between stereo images using RANSAC homography. 
3.	At time t, triangulate matching points using camera calibration data. Generate an active (visible) set using these 3D points at time t. 
4.	At time +1, extract interest points from both stereo images. Generate an active (visible) set using these 3D points at time t+1.
5.	From time t  to +1, match interest points in the images to determine overlap between the two 3D active sets. 
6.	Using the overlapping 3D points perform resection to estimate camera position and continue from step 2
•	Environment and develop kit:
1.	Matlab 2017a: still try to implement the project in C++ with opencv, while the debug process is too time-consuming. In purpose of finish the project on time, I have to switch to Matlab.
2.	Computer vision toolbox
