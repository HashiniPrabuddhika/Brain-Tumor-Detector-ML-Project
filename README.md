🧠 Brain Tumor Detector

This project uses deep learning to detect brain tumors from MRI scan images.
It leverages convolutional neural networks (CNNs) for image classification and provides an end-to-end pipeline for data preprocessing, model training, evaluation, and prediction.

🚀 Features

Preprocesses MRI scan images for training and testing.

Uses CNN for accurate brain tumor classification.

Supports visualization of training/validation accuracy and loss.

Can predict tumor presence on new MRI images.

🛠️ Tech Stack

Python 3.x

Jupyter Notebook

TensorFlow / Keras

NumPy, Pandas

Matplotlib / Seaborn for visualization

OpenCV / PIL for image processing

📂 Project Structure
Brain_Tumor_Detector/
│── Brain_Tumor_Detector.ipynb   # Main notebook
│── dataset/                     # MRI dataset (train/test)
│── models/                      # Saved trained models (if any)
│── README.md                    # Project documentation

⚡ Setup & Installation

Clone the repository:

git clone https://github.com/<your-username>/Brain_Tumor_Detector.git
cd Brain_Tumor_Detector


Install dependencies:

pip install -r requirements.txt


(or install manually: tensorflow, numpy, matplotlib, opencv-python, pandas)

Open the Jupyter Notebook:

jupyter notebook Brain_Tumor_Detector.ipynb

📊 Training & Testing

Load the dataset in the notebook.

Train the CNN model using the provided cells.

Evaluate accuracy, loss, and visualize predictions.

🔮 Prediction

You can test the model on new MRI scans:

model.predict(new_image)


It will output whether the scan indicates a Tumor or No Tumor.
