# CS 3GC3 - Project

## Contributors (Group 1)

- Mariana Mariles
- Sujan Kandeepan

## About 

The project requires implementation of an OpenGL-based 3D graphics program. 

## Proposal

	For the final OpenGL-based 3D graphics program project, my partner and I have decided to create an endless runner game. Specifically, players of our game will control a rocket and once the game commences, the rocket will launch into a tunnel where the player will have the point of view of the rocket from behind. 

	Throughout the game, the player will have to move through the tunnel between dangerous objects (for example, a bomb) and obstacles, such as rocks in order to remain playing. If the player happens to hit such an object, the rocket will blow up. Users will have the ability to rotate and move right, left, up and down while continuing forward. There will be coin-like objects which spin and shine once they are collected so that it is apparent to the player that it was retrieved as this will create more of an incentive for players to move the rocket from right to left, up and down for the duration of the game. In addition, there will be a timer set up so that players can try to beat their previous scores based on how long they survived.

## Features Implemented

- Lighting (tunnel, objects - 5%)
- Textures (coins, rocks, rocket - 10%)
- Alpha blending (display overlay - 5%)
- Particle systems (object collision - 5%)
- Animated characters (rocket, objects, particles, fire - 5%)
- Non-geometric primitives (rocket, objects, tunnel, text - 10%)

## Important Algorithms

- Object placement (randomized coordinates, weighted probability)
- Collision detection (calibrated according to display)
- Particle effects (randomized direction of particle movement)
- Fire animation (randomized placement/color of polygons)
- Smooth rocket movement (gradual change within display loop)
- Score flash on update (temporary change within display loop)
- Game over animation (color fade within display loop)
- Object file loader (parse file and populate data structures)
- Object depth sorting (introsort via std::sort, custom comparator)
- Infinite tunnel (set length and placement wrt. rocket/objects)

## Instructions to Compile

Run `make` to compile `main.cpp` and run `Project`.

## External Resources Referenced

- <https://github.com/SonarSystems/OpenGL-Tutorials/blob/master/Drawing%20A%20Hollow%20Circle/main.cpp>
- <https://www.khronos.org/registry/OpenGL-Refpages/gl4/html/glBlendFunc.xhtml>
- <https://stackoverflow.com/questions/39561997/glut-holding-a-key-down>
- <http://www.it.hiof.no/~borres/j3d/explain/light/p-materials.html>
- <http://www.opengl-tutorial.org/beginners-tutorials/tutorial-7-model-loading/>
- <https://learnopengl.com/Model-Loading/Model>
- <https://www.youtube.com/watch?v=MF1qEhBSfq4&list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6&index=1&ab_channel=Blender>
- <https://docs.blender.org/manual/en/2.80/addons/io_scene_obj.html>
- <http://opengl.czweb.org/ch13/433-436.html>
- <http://math.hws.edu/bridgeman/courses/324/s06/doc/opengl.html#blending>
- Frequently referenced OpenGL/GLUT and C++ documentation/examples.
- Sometimes referenced code examples from course slides and lectures.
- Sometimes referenced previous assignments and labs with similar code.
