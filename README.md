# Computer_Numerical_Control_CNC_Plotter
We are developing a CNC plotter centered around the PIC18F4520, capable of writing or drawing. By replacing the end effector with a cutting tool or laser generator, the plotter can be transformed into a CNC milling machine or laser engraver, making it highly versatile for advanced machining applications.

## **Introduction**
Computer Numerical Control (CNC) refers to the automated control of machining tools such as drills, lathes, grinders, milling machines, and 3D printers through computer systems. A CNC machine follows a pre-written program to transform raw material into a finished product without human intervention. This project serves as a preliminary step towards a CNC machine, focusing on position control by omitting the end effector.

Users input a target design, which is converted into path commands and processed by a microcontroller. The signals are then sent to stepper motors controlling the X and Y axes to manage position, while a servo motor adjusts the tool (pen) height for drawing.

# Demo Video

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/DwVW1ssXTtQ/0.jpg)](https://www.youtube.com/watch?v=3gOxqjiQkB4)
