# Colorize B&W Images

## Project Description
This app transforms grayscale images into vibrant, colorized versions. It leverages a pre-trained deep learning model to predict and fill in realistic colors for black-and-white images. The app provides a user-friendly interface built with Streamlit, enabling anyone to upload their images and instantly see them in color.

## Features
- Converts black-and-white images to color using deep learning.
- Simple and intuitive Streamlit-based UI.
- Processes images in real-time with efficient colorization algorithms.

## Technologies Used
- **Python**
- **OpenCV** for image processing.
- **NumPy** for numerical computations.
- **Streamlit** for web app development.
- **Deep Learning Models**:
  - `models_colorization_deploy_v2.prototxt`
  - `colorization_release_v2.caffemodel`
  - `pts_in_hull.npy`

## Installation
### Prerequisites
Ensure the following are installed:
- Python (>= 3.8)
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/colorize-bw-images.git
   cd colorize-bw-images
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the deep learning models and place them in the appropriate directory (e.g., `models/`).

## Usage
1. Run the application:
   ```bash
   streamlit run app.py
   ```

2. Open your browser and go to `http://localhost:8501`.

3. Upload a grayscale image (`.jpg` or `.png`) using the sidebar.

4. View the original and colorized images side-by-side.

## File Structure
```
colorize-bw-images/
|-- app.py                 # Main Streamlit application
|-- models/                # Pre-trained model files
|   |-- models_colorization_deploy_v2.prototxt
|   |-- colorization_release_v2.caffemodel
|   |-- pts_in_hull.npy
|-- requirements.txt       # List of dependencies
|-- README.md              # Project documentation
```

## Authors
- JVR Vinayak
- K Vamshi
- Contributors: Feel free to add your name here!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- The pre-trained models used in this project were inspired by the work of [OpenCV's deep learning model zoo](https://github.com/opencv/opencv).
- Special thanks to the creators of Streamlit for making web app development easy and interactive.

# SAR-Image-Colourization-For-Comprehensive-Insights-Using-DeepLearning
Done by JVR Vinayak 
