PR2 Surrogate
=============

This package enables fully immersive control of a PR2 robot using the Oculus Rift and Razer Hydra.

It uses rviz_oculus to render the Kinect's point cloud and the robot model to your Oculus headset,
while tracking your head motion with the PR2 head.
You use the Razer Hydra controller to drive the PR2 around and control it's grippers and torso lift,
while the poses of the Hydra paddles are directly mapped to the arm motion of the PR2.

Requirements:
 - Razer Hydra: https://github.com/aleeper/razer_hydra
 - Oculus Rift: https://github.com/ros-visualization/rviz_oculus
