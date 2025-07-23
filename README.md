# Computer Graphics Final Project

## Overview

The final project demonstrates the practical application of computer graphics principles including:

- 2D  transformations
- Projection and viewing
- Basic object rendering and manipulation
- Interactive control using keyboard and mouse inputs

The project was developed using **OpenGL** and C++, and aims to provide an interactive experience for manipulating 2D objects.

## Project Description

The project involves creating a environment where users can:

- Move objects with keyboard inputs
- Use keyboard inputs to adjust the view (day/night)
- Turn rain (On/Off) with keyboard inputs
- A menu which shows all key events

### Features:
- **2D Object Rendering:** Basic 2D shapes rendered using OpenGL.
- **Transformations:** Real-time transformations (scaling, rotation, translation) applied to the objects.
- **Interactive Controls:** Users can control object transformations via keyboard input.
- **Projection:** Implements perpective projection to simulate depth and realism in the scene.

## Technologies Used

- **Programming Language:** C++
- **Graphics Library:** OpenGL
- **IDE:** VS Code
- **Tools:** GLUT (OpenGL Utility Toolkit)

## How to Run

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AryanSaxenaa/BeachView.git
2. Ensure that OpenGL and GLUT are installed and configured properly on your machine.
3. Open the project in your preferred IDE (e.g., Visual Studio, Code::Blocks).
4. Build the project using g++ main.cpp src/Shapes.cpp src/KeyEvents.cpp -o BeachView -I./include -lfreeglut -lopengl32 -lglu32 -lwinmmS
5. ./BeachView.exe
[CG Project Report.pdf](https://github.com/user-attachments/files/21388319/CG.Project.Report.pdf)
