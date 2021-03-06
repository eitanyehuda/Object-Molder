# Object-Molder
3D Space where you can place, move, rotate and scale different objects.

![Screenshot1](https://user-images.githubusercontent.com/23744162/146408046-af30864d-3a06-4e13-9436-48c31286a954.png)
![Screenshot2](https://user-images.githubusercontent.com/23744162/146408732-eb389660-9681-4776-b353-b177ee0f7450.png)

Ray Tracing used to select objects with mouse, lighting, textures and matrix transformations.
Movement around world with middle mouse button and multiple objects can be selected

Etian Yehuda,
Thomas Britnell

*PPM processing code was taken from lecture code*

Usage:

S or s to save the file. You need to enter the file name in the command line and press enter.

O or o to open an existing file. You need to write a correct file name in the command line.

R to reset the scene.

Esc to exit the program.

[ and ] to change the selected light source.

l or L to toggle the lights on or off.

1 2 3 4 5 to switch betweeen the selected material. Also changes the material of the selected object (plastic, emerald, ruby, gold, pearl respectively).

q w e r t y to switch between the selected objects (cube, teapot, sphere, cone, torus, octahedron respectively).

Alt + z, x, and c to increase the selected object's scale in the z x and y directions. (Press shift at the same time to decrease the respective scales.

z, x, or c to translate the selected object in the z, x, and y directions. (Press shift at the same time to move in negative directions.)

b, n, or m to rotate the selected object in the z, x, and y directions. (Press shift at the same time to reverse the rotations.)

Click the left mouse button to select an object.

Hold shift and click to select a group of objects! This is our bonus feature.

Click and hold the middle mouse button to move around the scene.

Click the right mouse button to delete an object.


Design Decisions:

-Our special feature was that you can select a group of objects and are able to transform, rotate, change material, etc of all of them at once. 

-We also added a special camera movement style that allows smooth motion with the middle mouse button. This was not trivial, as it involves saving previous mouse positions and calculating a delta vector in order to change the scene rotation according to the chnage in mouse position. 


