#3D Visualization

## Overview

This app is developed as task for "Programming Computer Graphics" course.
There you can find visualization of first letter of my surname. In my case it was "Ш". You can draw this letter, repaint it with another color, move in different surfaces and rotate it.

## Used languages and frameworks:
  - C++
  - Qt Creator(Qt 5.14.2). Developed on Ubuntu(Linux).

## General object of the application:
- Main window with the coordinates.
- Button "draw letter" for drawing the object.
- LineEdits with the information(coordinates, angels).
- Different buttons for different operations with the object.
- Button "letter colour" for choosing object color.

## Used libraries:
- QMainWindow(frame of the application).
- QtOpenGL(gives classes of widgets OpenGL).
- QOpenGLFunctions(gives cross-platform access to API OpenGL ES 2.0).
- QOpenGlWidget(gives opportunity for showing OpenGL graphics integrated in Qt application).
- QColorDialog(gives opportunity for using special color choosing window QColorDialog).

## Implemented functionality:
- Displaying the first letter of my last name after pressing the "draw letter" button, namely the letter "Ш".
- The ability to select the color of the letter after pressing the "letter color" button.
- Setting the scale in LineEdits: "x scale", "y scale", "z scale".
- Displaying the resulting object after scaling with the "scaling" button.
- Specifying the transfer of a three-dimensional object in LineEdits: "x transfer", "y transfer", "z transfer".
- Displaying the obtained object after the transfer with the "transfer" button.
- Rotation around arbitrary axis in LineEdits: "rotation x", "rotation y", "rotation z".
- Displaying the obtained object after rotation with buttons: "rotation x", "rotation y", "rotation z".
 
## Note:
- This application was written using kits designed for Ubuntu.
- This application developed and may be executed on Windows. In folder executable there is file for starting the application.
