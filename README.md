# Dynamic Cityscape and Celestial Bodies Simulation
Welcome to the Dynamic Cityscape and Celestial Bodies Simulation repository. This project is designed to simulate a dynamic cityscape along with the movement of celestial bodies such as the sun, moon, and stars. The simulation is interactive and provides a visually appealing representation of both the urban environment and the night sky.

# Features
- **Dynamic Background**: The background color changes according to the time of day.
- **Buildings and Trees**: Various buildings and trees are drawn to create a cityscape.
- **Celestial Bodies**: The sun and moon move across the sky based on the time.
- **Birds**: Birds fly across the screen, and their positions are updated in real-time.
- **Clouds and Stars**: Clouds appear during the day, and stars appear at night.
- **Interactive Elements**: Clicking the mouse causes the birds to move.

# Installation

1. **Install Python**: Make sure you have Python installed. You can download it from [python.org](https://www.python.org/).

2. **Install Dependencies**: Use `pip` to install the required libraries.
    ```bash
    pip install PyOpenGL PyOpenGL_accelerate numpy
    ```

- Clone the Repository:
git clone https://github.com/yourusername/dynamic-cityscape-celestial-bodies.git
cd dynamic-cityscape-celestial-bodies

- Install Dependencies:
pip install -r requirements.txt

- Run the Simulation:
python main.py

# Usage
Once the simulation is running, you can use the following controls:

- Time Controls: Input time to get the sun and moon position.
- View Controls: Bird visual movements on mouse click.

# Configuration
You can customize various parameters of the simulation by modifying the config.json file. This includes:

- Cityscape dimensions and building styles
- Initial time and time factor
- Celestial bodies' appearance
- Movement patterns

# Technologies Used
- **OpenGL**: For rendering the graphics.
  - `OpenGL.GL`
  - `OpenGL.GLUT`
  - `OpenGL.GLU`
- **NumPy**: For numerical computations and handling arrays.
- **Python**: The programming language used for scripting the application logic.

## How It Works

- **Initialization**:
  - The window is initialized with specified dimensions.
  - Bird positions are initialized randomly.

- **Rendering**:
  - The background color changes based on the time of day.
  - Buildings, trees, and other elements are drawn using OpenGL functions.
  - The sun or moon is drawn based on the time.
  - Birds' positions are updated, and they are drawn on the screen.

- **Interactivity**:
  - Mouse clicks move the birds slightly.

## File Structure

- `main.ipynb`: The main script containing all the logic and functions.
