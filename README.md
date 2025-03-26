# FaceMetrics

## Overview
This project is an AI-powered Age and Gender Recognition system using deep learning. It utilizes Convolutional Neural Networks (CNNs) to predict the age and gender of individuals based on facial images.

## Features
- Detects and classifies gender (Male/Female) from images.
- Estimates age within a specified range.
- Uses a pre-trained deep learning model.
- Processes images efficiently for real-time applications.

## Technologies Used
- Python
- Jupyter Notebook
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Age-and-Gender-Recognition.git
   cd Age-and-Gender-Recognition
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Run the `Age_and_Gender_Recognition.ipynb` notebook.
3. Upload an image and get age & gender predictions.

## Dataset
This model is trained on the [UTKFace dataset](https://susanqq.github.io/UTKFace/) or a similar dataset containing labeled age and gender information.

## Results
- Achieves high accuracy in age and gender classification.
- Works well on diverse datasets but may have limitations in extreme lighting or occlusions.

## Future Improvements
- Enhance model accuracy with larger datasets.
- Improve real-time processing speed.
- Deploy as a web application.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
