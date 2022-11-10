# 5611Project3Web
 
David Buyck

VR IK

## [View the code on Github]([https://github.com/davidbuyck/5611Project2Code.git](https://github.com/davidbuyck/5611Proj3.git))

### Click on the images to play the YouTube videos!!!

## Part 1

#### Features attempted

Part 1 uses CCD

- Single-arm IK
- Multi-arm IK
- Joint limits
- User Interaction
- 3D Simulation & Rendering
- Skinned Models

[![Part 1](https://img.youtube.com/vi/cFDrOaxBpJs/0.jpg)](https://youtu.be/cFDrOaxBpJs)

### Single-arm IK (at least 2D)* (time: 0:00-1:07)
Each arm is a 4 joint (5 link) chain that roots at the center of the chest. See part 2's FABRIK video to see each joint/link in motion.
* 0:05 - 0:012 is when the controllers are out of reach. The pink dots are the VR controller positions.

### Multi-arm IK (time: 0:00-1:07)
There are 2 arms each with 4 joints and 5 links
* 0:05 - 0:012 is when the controllers are out of reach. The pink dots are the VR controller positions.

### User Interaction (time: 0:00-1:07)
I am controlling the position of the targets by moving the VR controllers with my hands in every video

### 3D Simulation & Rendering (time: 0:00-1:07)
This is in 3D with Unity’s XR VR packages. The camera is attached to the headsets position.

### Skinned Models
I use my own IK solver to move a robot humanoid model.

[![Joint Limit Video](https://img.youtube.com/vi/9TD8PFXhZL8/0.jpg)](https://www.youtube.com/watch?v=9TD8PFXhZL8)

### Joint limits (time: 0:00-0:38)
Rotational speed limits are used to limit each joint. The left hand has no speed limits in this video and moves around like wet spaghetti. The right arm in this video has the speed limits active and looks more like a human arm. The pink dots are the VR controller positions.


## Part 2

[![Part 2](https://img.youtube.com/vi/vCv5f3fFDcQ/0.jpg)](https://youtu.be/vCv5f3fFDcQ)

### FABRIK (time: 0:00-1:53)
I also implemented FABRIK as a solver for 3D IK.

Analysis:
FABRIK was easier to implement. There were no rotations needed for the FABRIK solver where CCD required rotations of each joint. I did not notice any difference in performance between the two methods. Both ran fast and contacted the targets when they were in reach. CCD is more flexible and supports constraints better. Since angles were used in CCD it was easier to put speed limits on the angles and make the motions more realistic. Where FABRIK looks like CCD without angle speed limits.
 

No partners we used. 

The simulations were made int the Unity Engine 2021.3.10f1. The UnityEngine and Unity XR packages were used. Models were all from the Unity Asset Store.

Art contest submissions:
![image](https://user-images.githubusercontent.com/47149695/201179864-cd98da87-9c6d-47f7-9041-a7f8371d83f2.png)



Let me know if you do not have access to the repo
