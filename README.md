# 5611Project3Web
 
David Buyck

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

[![Part 2](https://img.youtube.com/vi/h8vavKO2INo/0.jpg)](https://youtu.be/h8vavKO2INo)

### Single-arm IK (at least 2D)* (time: 0:00-1:30)
The flag is made up of multiple ropes that create a cloth

### Multi-arm IK (time: 0:00-1:30)
A cloth is created by connecting rows and columns of ropes. 

[![Joint Limit Video](https://img.youtube.com/vi/SNveAdVTFxk/0.jpg)](https://www.youtube.com/watch?v=SNveAdVTFxk)

### Joint limits (time: 0:00-1:30)
The cloth is created using 3D points with 3D positions, velocities, and forces.

### User Interaction (time: 0:00-1:30)
Meshes are used to render both sides of the flag

### 3D Simulation & Rendering (time: 0:00-1:30)
The cloth experinces air drag and the simulation has a wind coming off the top of the mountain creating the flapping effect of the flag.

### Skinned Models
The flag I created uses 3600 nodes and is simulated as a massive flag. The flag flys similar to the massive flag in the video above.

## Part 2

[![Part 2](https://img.youtube.com/vi/Aas1pQ7W5gs/0.jpg)](https://youtu.be/Aas1pQ7W5gs)

### FABRIK (time: 0:00-1:53)
I created a Shallow Water simulation that is seen as vertices of a mesh. I created islands and gave the mesh a water-like reflective material.

Difficulties:
I wanted to max out my CPU and GPU. So it took quite some time to find the right forces for the cloth where the nodes didnt stretch too much but also didnt break the simulation. I also made a SPH fluid dimulation but it was to computationally heavy to make a nice full scene. So I went with a Shallow Water simulation that allowed for more nodes and a full body of water.

No partners we used. 

The simulations were made int the Unity Engine 2021.3.10f1. The UnityEngine and Cinnemachine libraries were used. Models were all from the Unity Asset Store.

Art contest submissions:

![Flag](https://user-images.githubusercontent.com/47149695/196016667-c0105dd9-bf9d-4771-bd28-98f8d4d53fae.png)

![Waves](https://user-images.githubusercontent.com/47149695/196016682-35964d82-f2f8-46d9-8005-64c61415d3d1.png)


Let me know if you do not have access to the repo
