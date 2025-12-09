🚗 Real-Time License Plate Detection System

A real-time license plate detection system built using TensorFlow Lite and SSD MobileNet V2 FPNLite.

📌 Getting Started

Please read this Requirmnet.txt carefully before running the project.

🛠 Requirements

Install Python 3.7 from the official website:
https://www.python.org

⚠️ Important: If you have multiple Python versions installed, make sure Python 3.7 is selected as the default version for this project.


## 🎥 Project Demo

Watch the demo video here:  
https://youtu.be/Qt0bbXLapdI


Installation

Clone the repository

'git clone https://github.com/nicknochnack/TFODCourse .'
'cd anpr-system'

Create and activate virtual environment

'python -m venv anprsys'
# Windows
'anprsys\Scripts\activate'
# Linux/Mac
'source anprsys/bin/activate'

Install dependencies

'bashpip install --upgrade pip'
'pip install ipykernel'
'python -m ipykernel install --name anprsys'
'pip install tensorflow==2.4.1 '
'pip install opencv-python matplotlib pytz'
'pip install easyocr'
'pip install torch torchvision' --index-url https://download.pytorch.org/whl/cu118

Install TensorFlow Object Detection API

Follow the detailed setup instructions in the Jupyter notebook
Run verification script to ensure proper installation



Dataset
The project uses the Car Plate Detection dataset from Kaggle, containing:

433 vehicle images with corresponding XML annotations
Pre-labeled license plate bounding boxes
Training/testing split (approximately 80/20)

💻 Usage
Training the Model

Open main.ipynb in Jupyter Notebook
Execute cells sequentially through Step 6 to train the model
Training runs for 10,000 steps (configurable)
Model checkpoints saved automatically


🙏 Acknowledgments

TensorFlow Object Detection API team
EasyOCR developers
Kaggle dataset contributors
Nicholas Renotte for the comprehensive TensorFlow course

