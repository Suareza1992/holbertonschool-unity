Unity - Unity Concepts

Resources
Read or watch:

Unity Manual: GameObjects
GameObjects and Components
Creating GameObjects and Types of GameObjects
Unity Manual: Components
Components
Unity Manual: Prefabs
Creating and Using Prefabs
Unity Manual: Tags
Unity Manual: Layers
The Beginner’s Guide to Game Mechanics
The 13 Basic Principles of Gameplay Design (Read all 4 pages)
Gameplay and Game Mechanics Design: A Key to Quality in Videogames
Unity Manual
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is a GameObject
What is a Component
What is a Prefab
What is a Tag
What is a Layer
How to create and change the properties of a GameObject
How to create a Prefab
How to add Tags and Layers
Why is it important to name GameObjects and assets clearly and organize your project hierarchy
What are gameplay and game mechanics and how do they relate to developing any kind of interactive experience
Requirements
General
A README.md file, at the root of the folder of the project
Use Unity’s default .gitignore in your holbertonschool-unity directory – you may need to edit it so that it applies to your entire repo
Push the entire project folder unity_concepts to your repo, including .meta files – make sure that any files/folders in the .gitignore are not being pushed
Scenes and project assets such as Materials must be named and organized as described in the tasks
No scripts are allowed for this project
Tasks
0. Floor plans
mandatory
Create a new 3D Unity project called unity_concepts. Save your new scene as 0-floor. Create a new Cube GameObject named Floor with the following Transform properties:

Position: X: 0, Y: 0, Z: 0
Rotation: X: 0, Y: 0, Z: 0
Scale: X: 16, Y: 0.5, Z: 16
Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/0-floor.unity
 
2 correction requests
0/5 pts
1. On the ball
mandatory
Duplicate 0-floor by selecting the scene in the Project window and either Edit > Duplicate from the Toolbar or CTRL / CMD + D. Rename the scene 1-ball and open it. Create a new Sphere GameObject named Ball with the following Transform properties:

Position: X: 0, Y: 8, Z: 0
Rotation: X: 0, Y: 0, Z: 0
Scale: X: 1.5, Y: 1.5, Z: 1.5
Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/1-ball.unity
 
0/5 pts
2. Colors!
mandatory
Duplicate 1-ball, rename it 2-colors, and open it. Create a Materials folder in the Project window, then create a new material named floor. In the Inspector window, change the Albedo color to any color you like using the color picker. Assign the material to the Floor GameObject.

Create a second new material named ball. Change the material color and assign the new material to the Ball GameObject.

Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/2-colors.unity, unity_concepts/Assets/Materials/floor.mat, unity_concepts/Assets/Materials/ball.mat
 
0/12 pts
3. Gravity is a harsh mistress
mandatory
Duplicate 2-colors, rename it 3-gravity, and open it. Add a Rigidbody Component to the Ball GameObject. Press Play to see what happens. Wouldn’t it be better if the ball bounced when it fell?

Create a new folder in the Project window named Physic Materials and create a new Physic Material called bounce. Feel free to edit the material’s settings to get an idea of what the different settings affect. Add the bounce material to the Ball’s Sphere Collider. Press Play. For this task, your final bounce material settings should be:

Bounciness: 0.8
Bounce Combine: Maximum
Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/3-gravity.unity, unity_concepts/Assets/Physic Materials/bounce
 
0/7 pts
4. Prefabricated
mandatory
Duplicate 3-gravity, rename it 4-prefab, and open it. Create a new folder named Prefabs. Create a prefab from the Ball inside the new folder, then, using the prefab, add four more instance of the Ball to the scene. Position and scale them any way you like.

Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/4-prefab.unity, unity_concepts/Assets/Prefabs/Ball
 
0/4 pts
5. Even more colors!
mandatory
Duplicate 4-prefab, rename it 5-more_colors, and open it. Change the colors of each ball so they are different hex colors as defined below. New materials should be named as listed below. You cannot use scripts in this task.

ball-red : FF0000FF
ball-blue : 0000FFFF
ball-green : 00FF00FF
ball-white : FFFFFFFF
ball-black : 000000FF
Take a look at the Hierarchy window. Having a bunch of GameObjects with the same name is hard to navigate, right? It’s important to clearly name your GameObjects and assets, especially when working with others in the same project. Rename each Ball GameObject in your scene with their color name.

Red Ball
Blue Ball
Green Ball
White Ball
Black Ball
Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/5-more_colors.unity, unity_concepts/Assets/Materials/ball-*
 
0/10 pts
6. Tag yourself
mandatory
Duplicate 5-more_colors, rename it 6-tags, and open it. Add a tag to all Ball objects called Obstacles.

Repo:

GitHub repository: holbertonschool-unity
Directory: unity_concepts
File: unity_concepts/Assets/Scenes/6-tags.unity, unity_concepts/Assets/Prefabs/Ball.prefab

Author: Ángel Suárez (suarezangel.se@gmail.com)(Suareza1992)
