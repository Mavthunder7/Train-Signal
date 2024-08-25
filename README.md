# Train-Signal
Train Signal Simulation in OpenGL Introduction
This project is a simulation of a railway crossing using OpenGL, designed to illustrate the concepts and usage of pre-built OpenGL functions. The simulation showcases two connected railway tracks, where train signals control the movement of trains to prevent collisions.

Key Features
Simulates a railway crossing with two tracks.
Demonstrates the use of train signals to control train movement.
Allows interaction through keyboard inputs to control the signals and view the scene from different angles.
Project Overview
Software Requirements
Microsoft Visual C++
OpenGL
Hardware Requirements
Graphics System
Introduction to OpenGL
OpenGL is a software interface for graphics hardware that renders 2D and 3D objects into a frame buffer. These objects are described as sequences of vertices or pixels, which OpenGL processes to convert into the final image.

OpenGL Fundamentals
Primitives and Commands
Primitives: OpenGL draws points, line segments, or polygons, which are defined by vertices.
Commands: Commands in OpenGL are issued in the form of function calls to define primitives, set modes, and control other operations.
Basic OpenGL Operation
OpenGL processes data in a pipeline. Commands enter the pipeline, specifying geometric objects or controlling how these objects are handled during various processing stages.

Program Implementation
This project is implemented using various OpenGL functions:

glutInit(): Initializes the interaction between the windowing system and OpenGL.
glutInitDisplayMode(): Sets the display mode, including double buffering and depth information.
glutCreateWindow(): Opens the OpenGL window and sets the window title.
glutInitWindowSize(): Specifies the window size.
glutInitWindowPosition(): Specifies the window's position on the screen.
glutKeyboardFunc(): Handles normal ASCII keyboard input.
glutSpecialFunc(): Handles special keyboard keys.
glutReshapeFunc(): Sets up the callback function for reshaping the window.
glutIdleFunc(): Handles background processing.
glutDisplayFunc(): Manages redrawing the window.
glutMainLoop(): Starts the main loop of the program, which never returns.
glViewport(): Sets up the viewport.
glVertex3fv(): Sets up points or vertices in 3D space.
glColor3fv(): Applies color to faces.
glFlush(): Flushes the pipeline to ensure all commands are executed.
glutPostRedisplay(): Triggers a redraw of the object.
glMatrixMode(): Sets the required matrix mode.
glLoadIdentity(): Loads or initializes to the identity matrix.
glTranslatef(): Moves the rotation center to a new point in 3D space.
glRotatef(): Rotates an object by a specified angle.
Interaction with the Program
This simulation includes interaction through keyboard controls:

P: Start the simulation.
1: Toggle signal 1 (top).
2: Toggle signal 2 (bottom).
3: Toggle both signals simultaneously.
X/x: Rotate the scene around the X-axis.
Y/y: Rotate the scene around the Y-axis.
Z/z: Rotate the scene around the Z-axis.
Q: Quit the simulation.
Conclusion
This project effectively demonstrates the use of OpenGL for simulating a railway crossing, showcasing the ability to control and interact with a 3D scene through keyboard inputs. It serves as a practical example of using OpenGL functions to create interactive graphics applications.
