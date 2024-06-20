# NOSTRESS.AI now!

Hiii welcome to NoStress.ai a Machine Learning Model trained to help you monitor your stress levels. 
Stress Level Monitoring Machine Learning Model
Overview

This project aims to help people monitor their stress levels using machine learning techniques. The model predicts stress levels based on various physiological and environmental factors. The dataset used (data_stress.csv) was obtained from Kaggle and contains relevant features for stress prediction.

Dataset
The dataset (data_stress.csv) includes the following columns:
- snoring range
- respiration rate
- body temperature
- limb movement
- blood oxygen
- eye movement
- hours of sleep
- heart rate
- Target (Stress Level)
Key Findings
After extensive data preprocessing and model training:

Optimizations were applied that significantly improved the performance of the model.
The final model achieved 100% accuracy on training and 99.21% on the test set.
Instructions
Running the Notebook
To run the Jupyter Notebook (NoStress.ipynb):

Ensure you have Python 3.x installed.
Install Jupyter Notebook using pip if not already installed:
Copy code
pip install notebook
Clone the repository:
bash
```git clone https://github.com/yourusername/your-repository.git```
Navigate to the project directory:
bash
```cd your-repository```
Start the Jupyter Notebook:
```jupyter notebook```
In the Jupyter Notebook interface, navigate to stress_level_prediction.ipynb and open it.
Loading Saved Models
Models were saved using Keras in the HDF5 format (model.h5). To load the saved model in Python using Keras:

python
``` from keras.models import load_model

# Load the model
model = load_model('path_to_your_model/model.h5')

# Example of how to use the loaded model for prediction
# input_data should be a numpy array containing the input features
predictions = model.predict(input_data)
Replace 'path_to_your_model/model.h5' with the actual path where model.h5 is saved.
```

