# FameFinder
This ML project uses TensorFlow and MobileNet V2 to train a model that recognize faces from images, trained with over 2500+ images with a high accuracy
The model is suitable for real-world applications in recognizing people

# Dataset
The dataset is from Kaggle and consists of images stored in two directories:
- **Faces:** Pre-processed images of faces.
- **Original Images:** The original images containing faces

# Installation
To run this project, follow these steps:

- Clone the repository:
```bash
git clone https://github.com/your-username/face-recognition.git
```
- Install the required Python packages:
```bash
pip install -r requirements.txt
```
- Mount Google Drive and set up the paths:
```bash
from google.colab import drive
drive.mount('/content/drive')

dataset_csv = "/content/drive/MyDrive/Face recognition/Dataset.csv"
faces_images_path = "/content/drive/MyDrive/Face recognition/Faces/Faces"
original_images_path = "/content/drive/MyDrive/Face recognition/Original Images/Original Images"
```
