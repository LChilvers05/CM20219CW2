# Fundamentals of Visual Computing
## Coursework 2 - WebGL

This README will briefly explain the interactions the user will need to view the requirements outlined in the specification.

### Requirement 3 - Rotate the cube
To rotate the cube around the x-, y- and z-axis respectively, press the 'X', 'Y' and 'Z' keys. Each key down event for these keys will toggle the animation running and will reset the cubes rotation.  
A future development for this requirement is to smoothly transition between the different rotations so reseting the state of the cube is not obvious.

### Requirement 4 - Different render modes
The cube is initialised in face render mode.  
To see vertex render mode, press 'V' key.  
To see edge render mode, press 'E' key.  
To return to face render mode, press 'F' key.  

### Requirement 5 - Translate the camera
Press up arrow/down arrow keys to move the camera on its forward/backward vectors.  
Press the left/right arrow keys to move the camera on its left/right vectors.  
Press the '1' key to move on the up vector, and the '2' key to move along the camera's down vector.

### Requirement 6 - Orbit the camera
**Please note the camera will orbit its look-at point.** To make the camera look at the origin again (centre of the cube) no matter its position, press the '0' key.  
To orbit the camera latitudinally, press the 'A' and 'D' keys.  
To orbit the camera longitudinally, press the 'W' and 'S' keys.  


## Requirement 7 - Texture mapping
A local webserver must be started for this requirement because local files on the drive must be accessed by the browser.  
To map different textures onto the different faces of the cube, press the 'T' key.

## Requirement 8/9 - Load a mesh model from .obj, rotate the mesh and render it in different modes

Pressing the 'B' key will load the bunny model and scale it in an edge cube.  
The 'N' key will show the model in vertex render mode.  
The 'M' key will show the model in edge render mode.  
From here, the model can be rotated in the cube using the same commands as before ('X', 'Y', 'Z' keys).  

# Requirement 10 - Plane game

Before opening the game, a local webserver must be started to access **Req10.html** from.

## Aim
The aim of the plane game is very simple: Fly through all ten rings as quickly as possible. Rings are randomly positioned in the map each game and will turn green when they have been successfully flown through.  A good attempt will be completed in under a minute.  The game will reset automatically when completed after a break of 10 seconds.

There is a label in the top right that will inform you of the number of targets still to get and the amount of time this attempt has been running.

## Controls
To control the plane:
- Up Arrow key will increase the plane's altitude.
- Down Arrow key will decrease the plane's altitude.
- Right Arrow key will turn the plane right.
- Left Arrow key will turn the plane left.
- The Space Bar will give the plane a short speed boost.