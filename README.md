Abstract

Main Aim:

To illustrate the concepts and usage of Congestion Control in OpenGL.

Key Points:

Definition: Network congestion occurs when a link or node is overloaded with data, causing quality of service to deteriorate.
Problem: Excessive packets lead to intermediate routers discarding packets, causing retransmissions and further congestion.
Impact: Congestion collapse where throughput is negligible due to most packets being lost.
User Interaction: The program allows interaction via mouse and keyboard.

System Specifications

Software Requirements:

Microsoft Visual C++: Development environment for writing and debugging the program.
OpenGL: Graphics library for rendering 2D and 3D vector graphics.

Hardware Requirements:

Graphics System: Essential for rendering graphical output.
Minimum Specs: Pentium P4 with 256MB RAM.

Introduction to OpenGL

Purpose:

OpenGL is a software interface to graphics hardware for rendering 2D and 3D objects.

Object Description:
Objects are described as sequences of vertices or pixels processed through various stages to form the final image in the frame buffer.

OpenGL Fundamentals:

Primitives and Commands:

Primitives: Points, lines, and polygons.
Commands: Function calls to specify primitives and set rendering modes.
Vertices: Define points, line endpoints, or polygon corners.
Modes: Different settings that affect rendering.

Basic Operation:

Pipeline: Commands flow through a processing pipeline.
Display Lists: Accumulate commands for later processing.
Rasterization: Converts descriptions into frame buffer addresses and values.
Per-Fragment Operations: Final operations before storing pixels in the frame buffer.

Implementation

OpenGL Functions Used:

Initialization:

glutInit(): Initializes the OpenGL environment.
glutInitDisplayMode(): Sets the display mode.
glutCreateWindow(): Creates a window for rendering.
glutInitWindowSize(): Sets the window size.
glutInitWindowPosition(): Sets the window position.

Event Handling:

glutKeyboardFunc(): Handles keyboard input.
glutSpecialFunc(): Handles special keyboard keys.
glutReshapeFunc(): Handles window reshaping.
glutIdleFunc(): Background processing.
glutDisplayFunc(): Redraws the window.
glutMainLoop(): Starts the main event loop.

Rendering:

glViewport(): Sets up the viewport.
glVertex3fv(): Specifies vertices.
glColor3fv(): Specifies colors.
glFlush(): Flushes the OpenGL pipeline.
glutPostRedisplay(): Requests a redraw.
glMatrixMode(): Sets the current matrix mode.
glLoadIdentity(): Loads the identity matrix.
glTranslatef(): Translates the position.
glRotatef(): Rotates the object.

Interaction

User Controls:

Keyboard:

S: Start the project.
Q: Quit the project.

Mouse:

Right Mouse Button: Opens a menu to choose options.

Source Code

Header Files:

Necessary includes for OpenGL and other libraries.

Variable Declarations:

Variables for object positions, movement, and states.

Function Definitions:

Text Functions:
setFont(): Sets the current font.
drawstring(): Draws a string at a specified position.
stroke_output(): Outputs stroke characters.
Shape Functions:
cloud(): Draws a cloud shape.
router(): Draws a router.
dte(): Draws a data terminal equipment.
line(): Draws a line.
rack(): Draws a rack.
window(): Draws a window.
top(): Draws the top of a house or building.
Animation and Rendering Functions:
animate(): Handles animations.
network(): Draws the network with various components.

Output

Display:
Shows the output of the congestion control simulation with graphical elements representing the network and data flow.

Conclusion

Summary:
Recaps the implementation and significance of congestion control in networking.

Outcome:
Describes the results achieved by the simulation.

Future Work:
Suggests improvements and future enhancements.

Bibliography

References:

TEXT BOOKS : 

INTERACTIVE COMPUTER GRAPHICS A TOP-DOWN APPROACH 
-By Edward  Angel.   

COMPUTER GRAPHICS,PRINCIPLES & PRACTICES
                                 -By Foley van dam &
			                           Feiner  hughes

WEB REFERENCES:   

http://jerome.jouvie.free.fr/OpenGl/Lessons/Lesson3.php

http://google.com
http://opengl.org

