# Rubic-cube-problem-solver
 To design and implement a system that can detect, analyze, and solve a standard 3×3 Rubik's Cube  using a webcam and Python libraries. The system captures the six faces of the cube, identifies the  colors of each sticker using computer vision and machine learning.
Tools and Technologies Used- Python 3.x: Programming language- OpenCV: Computer vision for image capture and processing- NumPy: Array and matrix manipulation- scikit-learn: Machine learning (KMeans clustering)- Kociemba Solver: Rubik's Cube solving algorithm- Matplotlib / Tkinter (optional): Visualization- VS Code or Jupyter Notebook: Code editor/IDE
 Workflow / Process
 Step 1: Environment Setup
  - Install Python and required libraries using pip.
  - Install Microsoft C++ Build Tools if prompted.
 Step 2: Capture Cube Faces
  - Use webcam to capture images of each cube face.
 Step 3: Detect Stickers (Contours)
  - Apply thresholding and contour detection to identify sticker regions.
Step 4: Color Detection
  - Use HSV ranges or KMeans clustering to classify sticker colors.
 Step 5: Reconstruct Cube State
  - Combine detected face data into a 54-character string representing the cube state.
 Step 6: Solve the Cube
  - Use kociemba Python library to generate a solution.
 Step 7: (Optional) Visualization
  - Animate solution using OpenCV or matplotlib.
 Features- Real-time color detection- Webcam-based face capture- ML for color clustering- Optimal solving using Kociemba algorithm- Optional simulation and animation
 Applications- Education for vision and algorithms- Robotics and automation- Puzzle analysis and recognition
 Future Improvements- Add CNN for color classification- Support 2×2 and 4×4 cubes- Robotic arm integration
- Better user interface
 Conclusion
 This project demonstrates a practical application of computer vision and machine learning by solving
 a Rubik's Cube. The system effectively captures, interprets, and solves the cube using visual data
 and algorithmic reasoning, serving as a bridge between AI and real-world problem solving.
