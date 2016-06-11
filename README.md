# OpenGl-scripts

Hello guys,<br>
This repo contains my OpenGl work that I've been learning for sometime now.<br
A list of items:<br>
1.)<b>Bounce3D</b> : This script generates 3D balls bouncing on a platform.It has key controlled camera.Use the arrow keys to see the project at different angles.<br>
2.)<b>Light torus</b> : Generates a controllable mesh.What I mean by that is you can control the quality of the mesh of a torus in real-time on the command of just a few key strokes.<br>
3.)<b>Moon</b>: Generates a rotating sphere of the appearance of moon, showing the different phases of Moon.<br>
4.)<b>Teapot</b> : Generates a teapot with a light source revolving around it,showing the different views of it accordingly.<br>
5.)<b>Torus</b> : Generates a constantly rotating torus

## How to compile and run these files?

Compiling these files is really easy and done via a simple command in the terminal:

```c
gcc -o 'yourOutputFileName' 'theCFileName' -lGL -lGLU -lglut -lpthread -lm
```
for example if you wanted to check the **controlMesh.c**, the command would be:
```c
gcc -o controlTheMesh controlMesh.c -lGL -lGLU -lglut -lpthread -lm
```
this will create an executable file named *controlTheMesh* on your system. Just open and see the magic going.
