# Unity-NavMesh-Demo

A template and demo project for Unity navigation meshes and pathfinding. It includes a sample scene with baked navigation meshes, dynamic and static obstacles, off mesh links and a navigation agent.

**[You can find complete Unity project folder and APK files in here.](https://drive.google.com/drive/folders/1btcns6OKTNlP4kPshp44c_Oq3RMgQD51?usp=sharing)** Since, GitHub has file count and size limitations, I have uploaded the project to Google Drive.

Project has been developed on Unity 2021.1.23f1. If you are facing with errors, **please check your Unity and package versions**. Please keep in my that using different versions may result with errors.


Following screenshot has taken from sample scene. Small yellowish part of the plane on the upper side is demostrated as sandy area which has a higher cost. Moving on this sandy area has a higher cost for the agent, so it avoids to use there if it is possible. The green box is a dynamic obstacle, when it is moved the agent recalculates its route to target. However, you can move the dynamic obstacle only in Unity Editor. To be able move it on Android, you can use raycasting just like i used for the agent.

<img src="/Images/NavMesh.jpg" width="800" height="360">

The agent cannot climb over small boxes. You can check "walkable" areas in the Unity Editor (Window > AI > Navigation). Following image shows both baked navigation and height meshes, walkable areas and off mesh links between meshes.

<img src="/Images/Meshes.jpg" width="800" height="315">

To set a target for the agent, just tap to any point you deserve on the screen. A blue circle will be animated when you tap any proper point. As an example, you can watch the following video which has taken from an Android device.

https://user-images.githubusercontent.com/40580957/139305933-1006d16c-e55a-4879-9519-7563a515a777.mp4

