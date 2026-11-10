# AI-Powered 3D Hand Gesture Controlled Rubik's Cube

An AI-powered virtual 3D Rubik's Cube application that allows users to interact with and solve a virtual cube using real-time hand gestures through a webcam, without requiring a physical cube, mouse, or keyboard.

## Project Overview

This project combines computer vision, hand gesture recognition, and 3D graphics to create an interactive Rubik's Cube experience.

Using a webcam, the application tracks hand movements and translates gestures into cube operations. The virtual 3D cube is rendered over the live webcam feed, providing an augmented reality-like interaction experience.

## Key Features

### 1. Touchless Hand Gesture Control
- Real-time hand tracking using MediaPipe.
- Finger pinching and swiping gestures to control cube layers.
- Open-hand and fist gestures for rotating the cube view.

### 2. 3D Rubik's Cube Visualization
- Interactive 3D Rubik's Cube rendering.
- Integration of OpenGL graphics with a live webcam feed.
- Smooth and interactive cube movements.

### 3. Air Mouse Control Dashboard
- Gesture-based dashboard interaction.
- Hover-based button selection.
- Touchless navigation through application controls.

### 4. Gameplay and Learning Modes

**Challenge Mode**
- Timer-based gameplay.
- Score tracking.
- Move counter.
- Local leaderboard to save performance records.

**Practice Mode**
- Camera-based scanning of all six cube faces.
- Step-by-step solving guide.
- Interactive learning experience.

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyOpenGL
- GLFW
- NumPy
- JSON

## Project Architecture

The application integrates multiple technologies:

1. **Computer Vision:** Captures and processes live webcam frames using OpenCV.
2. **Hand Tracking:** Detects hand landmarks and recognizes gestures using MediaPipe.
3. **Gesture Processing:** Converts hand movements into application commands.
4. **3D Rendering:** Creates and displays the virtual Rubik's Cube using PyOpenGL and GLFW.
5. **Data Management:** Uses JSON for storing leaderboard information.

## Installation and Setup

### Prerequisites
- Python 3.x
- Webcam
- Required Python libraries

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Powered-3D-Hand-Gesture-Rubiks-Cube.git
```

### Step 2: Navigate to the Project Folder

```bash
cd AI-Powered-3D-Hand-Gesture-Rubiks-Cube
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Run the Application

Run the main Python file:

```bash
python src/main.py
```

Note: Update the execution command according to the actual location of your main Python file.

## Application Requirements

- A working webcam.
- Proper lighting for accurate hand tracking.
- Python and the required dependencies installed.

## Future Enhancements

- Improved gesture recognition accuracy.
- Enhanced cube-solving algorithms.
- Additional interactive learning features.
- Improved user interface and performance.

## Author

**Jifhna P N**

MCA Graduate | AI & Machine Learning Enthusiast

[GitHub](https://github.com/YOUR-USERNAME)

