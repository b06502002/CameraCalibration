# CameraCalibration

Steps for camera calibration:
- Prepare a checkerboard. Measure the grid width of the checkerboard to confirm its dimension.
- Place your camera in a fixed point and fix the focal length. Turn off the auto-focusing functionality if it is open as default. For some smartphones, this can be done in "Expert mode."
- Capture images of checkerboard in different position and orientation within the frame. Like the ones shown in Figure 3.
In theory, at least 3 images are needed. To obtain better calibration result in practice, around 20 images are sufficient.

A rule of thumb is to capture the checkerboard in almost everywhere in the frame. Make sure the checkerboard has located in each corner of the frame. Also, do not leave a portion of a checkerboard out of the frame because the calibration algorithm will fail to detect the grid points.
- Open the code editor and copy the source code from this GitHub page. Import the photos to the same folder as the python code.
- Change the checkerboard size, grid width and the frame size. Compile the code.
- In the terminal, the camera matrix is shown. This corresponds to the intrinsic parameters, which is the $K$ matrix we mentioned in the labwork handout. 
