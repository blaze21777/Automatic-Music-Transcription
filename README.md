# Automatic Music Transcription

This project aims to use audio files of guitars to create and train a neural network to identify which
notes are being played and transcribe the notes into guitar tablature.

## Creating Datasets

---
The folder Guitar Simulation contains the file **Audio_Data_From_Matlab.py**, this is used to create the notes specified in the **Notes_to_Frequency.py** file.

* To run the script the Matlab engine is required: [Tutorial here](https://stackoverflow.com/questions/51406331/how-to-run-matlab-code-from-within-python)

* To convert the wav files to JSON files run **save_dataset.py**

## Data Visualisation  

---
The **Display_MFCC.py** script can be used to the spectrograms and MFCC of the specified audio file.

## Running the Models

---
**CNN.py** and **LSTM.py** are used to create the models and save the models, these model can then be used for prediction by running **CNN_Predict.py** or **LSTM_Predict.py**
