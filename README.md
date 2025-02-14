# Pneumonia Detection using CNN

This project aims to detect pneumonia from chest X-ray images using Convolutional Neural Networks (CNN). The model is built using Keras with TensorFlow backend. The web application is developed using Flask framework to provide a user-friendly interface for uploading images and getting predictions.

## Requirements
- Anaconda (for creating virtual environment)
- Python 3.6 or above
- Flask==1.0.2
- Keras==2.3.1
- jupyter==1.0.0
- Pillow==5.4.1
- numpy
- scikit-learn==0.20.2
- tensorflow==2.2.0
- matplotlib==3.0.2

## Setting Up Environment
1. Install Anaconda if not already installed.
2. Create a new virtual environment:----conda create -n pneumonia_detection python=3.6
3. Activate the virtual environment:
----conda activate pneumonia_detection	
4. Install required packages using pip:
----pip install -r requirements.txt
5. Ensure you have Jupyter Notebook installed for building notebooks.

## Datasets
- [COVID-19 Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset)
- [Coronahack Chest X-ray Dataset](https://www.kaggle.com/datasets/praveengovi/coronahack-chest-xraydataset)

## Usage
1. Clone the repository:
----git clone https://github.com/alexmathew2009/Pneumonia-detection-CNN.git
----cd Pneumonia-detection-CNN
2. Download datasets from the provided links and place them in the appropriate directories within the project structure.
3. Build and train the model using Jupyter notebooks provided in the `notebooks` directory.
4. Once trained, develop the Flask application using HTML/CSS for the web interface.
5. Start the Flask application:
----python app.py
6. Open your web browser and go to `http://localhost:5000` to access the application.
7. Upload chest X-ray images to get predictions for pneumonia detection.	

## Contributing
Contributions are welcome. If you find any issues or improvements, please open an issue or create a pull request.
