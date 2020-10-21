# Lane detector for self driving cars

Lane detection is used for trajectory planning for self driving cars, since it detects pixels in the image which belongs to the drivable surface.

The following approach is used :

1.	Camera calibration and perspective projection to obtain accurate lane trajectory.
2.	Combine sobel filter and HSL colour space to extract lane.
3.	Use algorithm to find points for left and right lanes.
4.	Fit points to polynomial to obtain parametric trajectory needed for path planning.
5.  Obtain polygon enlcosed by road lanes which is the drivable surface.


Input frame:
![alt text](https://i.ibb.co/qW2jGt8/Untitled.png)


Output frame
![alt text](https://i.ibb.co/s9hmFBL/Untitled2.png)
