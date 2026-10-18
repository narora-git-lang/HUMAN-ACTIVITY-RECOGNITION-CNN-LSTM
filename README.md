# Human Activity Recognition Using CNN-LSTM

## Overview

This project focuses on Human Activity Recognition (HAR) using smartphone sensor readings and deep learning. It uses a hybrid CNN-LSTM model to classify human activities based on motion data collected from smartphone sensors.

The CNN extracts useful patterns from sensor readings, while the LSTM learns temporal relationships between consecutive readings.

The project focuses on four activities:

- Walking
- Jogging
- Sitting
- Standing

## Problem Statement

Human Activity Recognition is an important part of wearable technology, healthcare monitoring, and human-machine interaction. Smartphone sensors collect motion data that can be used to identify different physical activities.

The objective of this project is to develop a deep learning model that classifies human activities from sensor data using a combination of CNN and LSTM architectures.

## Dataset

This project uses the WISDM Smartphone and Smartwatch Activity and Biometrics Dataset.

- **Dataset on Google Drive:** [Access the dataset](https://drive.google.com/drive/folders/17jQ6t8h5qv-O1aBZsBrP_ResLvaRITGP?usp=sharing)
- **Original dataset source:** [WISDM Dataset on UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/507/wisdm+smartphone+and+smartwatch+activity+and+biometrics+dataset)

The dataset contains sensor readings used to train and evaluate the human activity recognition models.

Make sure the Google Drive folder is accessible to viewers with the link.

## Project Workflow

1. Download and extract the dataset.
2. Load smartphone sensor readings.
3. Select the target activity classes.
4. Clean and preprocess the sensor data.
5. Create fixed-size time windows from the sensor features.
6. Split the data into training and testing sets by participant.
7. Scale the sensor features.
8. Build and train the CNN-LSTM model.
9. Evaluate the model using accuracy, loss, a classification report, and a confusion matrix.
10. Compare the CNN-LSTM model with a CNN-only model.

## Model Architecture

### Convolutional Neural Network (CNN)

The CNN identifies local patterns and features in the sensor data. These patterns help distinguish the movement characteristics of different activities.

### Long Short-Term Memory (LSTM)

The LSTM processes sequential information and learns temporal dependencies between sensor readings.

### CNN-LSTM

The combined architecture uses CNN layers to extract features and LSTM layers to learn how these features change over time. This helps the model classify activities using both motion patterns and temporal relationships.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab
- Jupyter Notebook

## How to Run the Project

1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Allow the notebook to download and extract the dataset.
4. Execute the preprocessing cells.
5. Train the models.
6. Review the evaluation metrics and visualizations.

**Note:** Training time may vary depending on the execution environment.

## Results and Evaluation

The notebook includes the following evaluation outputs:

- Training and validation performance
- Test evaluation metrics
- Classification report
- Confusion matrix
- CNN-LSTM and CNN-only model comparison

Refer to the notebook outputs for the actual evaluation results.

## Repository Contents

- `HumanActivityRecognitionCNNLSTM_Simplified.ipynb` - Jupyter Notebook containing the project implementation, code, and existing outputs.

## Authors

- Nishad Arora
- Adrita Ghosh
- Shwetaleena Mohanta
- Ayush Singh
- Krishan Goyal

## Future Scope

- Extend the model to recognize additional human activities.
- Explore other deep learning architectures.
- Improve generalization across different users and devices.
- Investigate real-time activity recognition using smartphone sensor data.

## Notes

- The notebook is designed to run in Google Colab.
- Dataset files are not included in the GitHub repository.
- The simplified notebook preserves the existing outputs and results.
- The notebook has not been rerun as part of preparing this README.
