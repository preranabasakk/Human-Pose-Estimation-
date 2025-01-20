Project Title: The project is titled "Human Pose Estimation Using OpenCV and Streamlit."

Objective: Detects and visualizes human body keypoints (e.g., head, shoulders, wrists, etc.) from images using a pre-trained TensorFlow model.

Features:

Upload and process custom images.
Visualize detected keypoints and skeleton connections.
Adjustable detection threshold via a Streamlit slider for fine-tuning results.
Technology Stack:

OpenCV: For image processing and pose detection.
TensorFlow: Pre-trained deep learning model (graph_opt.pb).
Streamlit: For creating an interactive web interface.
Python Libraries: NumPy, PIL (Pillow), and Matplotlib.
Prerequisites: Python 3.7+ and necessary Python libraries installed via pip install -r requirements.txt.

Project Setup:

Clone the repository and navigate to the project directory.
Place the graph_opt.pb model file in the project directory.
Include a sample image (e.g., stand.jpg) for demonstration.
Running the App: Start the Streamlit app with streamlit run app.py, then access it via your browser on http://localhost:8501.

Threshold Slider: The app includes a slider to adjust the confidence threshold for keypoint detection, improving the precision of pose estimation.

Output: Displays two images: the original image and the processed image with pose estimation results (keypoints and skeleton overlay).

Potential Use Cases: Applications in fitness, sports analytics, motion tracking, and real-time pose monitoring systems.
