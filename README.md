# face-mask-detection-keras

Face Mask Detection Using Keras
This project is a Python-based face mask detection system implemented with Keras, TensorFlow, and OpenCV. It identifies whether a person is wearing a mask or not, using a trained deep learning model.

Features
Real-time mask detection using a webcam or video feed.
Pre-trained model built on a labeled dataset for accurate classification.
Simple and easy-to-use implementation with Python and OpenCV.
Credits and Inspiration
This project is built upon the dataset and ideas from the following contributors and resources:

Prajna Bhandary: Original dataset, available on GitHub.
Adrian Rosebrock: Tutorials and guides on deep learning for computer vision.
sentdex: Educational resources on AI and Python.
Video Tutorial: Face Mask Detection on YouTube.
Technology Stack
Deep Learning Framework: Keras and TensorFlow
Computer Vision Library: OpenCV
Language: Python
Dataset
The dataset consists of labeled images of people with and without masks, prepared by Prajna Bhandary. It forms the foundation for training the detection model.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/face-mask-detection-keras.git  
cd face-mask-detection-keras  
Install dependencies:

bash
Copy code
pip install -r requirements.txt  
Run the script to test detection:

bash
Copy code
python detect_mask.py  
How It Works
The model is trained using a labeled dataset of images with and without face masks.
OpenCV is used to preprocess input images and video feeds.
The trained deep learning model predicts mask presence in real time.
Future Enhancements
Adding support for edge devices like Raspberry Pi.
Improving accuracy by training on larger datasets with diverse populations.
Extending functionality to detect proper mask usage (e.g., masks covering the nose).
License
This project is licensed under the MIT License.

Bringing safety and awareness through AI and computer vision. 🚀
