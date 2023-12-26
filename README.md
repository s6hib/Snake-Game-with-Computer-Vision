### Introduction
This project is a unique take on the classic Snake game, integrating computer vision to control the snake using hand movements. It's built using Python and libraries like OpenCV and cvzone.

### Prerequisites
- Python 3.x
- OpenCV (cv2)
- cvzone
- NumPy
- A webcam

### Installation
1. **Install Python 3**: If not already installed, download and install Python 3 from [python.org](https://www.python.org/downloads/).

2. **Install Required Libraries**: Open a terminal or command prompt and run the following commands:
   ```bash
   pip install opencv-python
   pip install cvzone
   pip install numpy
   ```

3. **Clone the Repository**: Clone this repository to your local machine or download the source code.

   ```bash
   git clone https://github.com/s6hib/Snake-Game-with-Computer-Vision.git
   ```

4. **Navigate to the Repository Folder**: Change directory to the folder where the game code resides.
   ```bash
   cd path/to/Snake-Game-with-Computer-Vision
   ```

### Running the Game
1. **Start the Game**: Run the Python script.
   ```bash
   python snake_game_cv.py
   ```

2. **Playing the Game**: 
   - The game uses your webcam to track hand movements.
   - Move your hand to control the direction of the snake.
   - Capture the food (Donut.png) to grow the snake and increase the score.
   - Avoid hitting the snake's body with its head.

3. **Restarting the Game**: Press the 'r' key to restart the game after a game over.

### Additional Notes
- Ensure good lighting for accurate hand tracking.
- The hand tracking may not work properly if multiple hands are detected or in poor lighting conditions.
- The game uses the image 'Donut.png' as food for the snake, ensure this file is in the same directory as the game script.

### Troubleshooting
- If the game doesn't start, check if all dependencies are properly installed.
- Make sure your webcam is functioning and accessible by the script.
- For any other issues, feel free to raise an issue in the repository.

Enjoy playing the Snake Game with a twist of Computer Vision!
