# ITrash

To view a demonstration of ITrash: https://www.youtube.com/watch?v=2cf8Vxe4Su0

ITrash is an autonomous trash can that can detect projectile garbage, calculate its trajectory, and predict where it will land and move accordingly to catch it.

ITrash uses OpenCV to detect the motion of the trash. A Raspberry Pi with a camera module is placed on a wall to take a stream of pictures whenever a moving object is detected. Two pictures and the time interval between them are then used to calculate the estimated landing position.
