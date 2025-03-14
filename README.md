# Convolutional Neural Networks (CNN) Project

## Overview
This project explores the implementation and application of Convolutional Neural Networks (CNNs) using Python and popular deep learning libraries. CNNs are widely used for image recognition and classification tasks due to their effectiveness in extracting spatial features from images.

## Project Structure
- `cnn_model.py`: Python script containing CNN architecture, training, and evaluation.
- Dataset: Included in the project or referenced from an external source.

## 📂 Data

The project utilizes image data suitable for CNN training, validation, and testing purposes, specifically the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset.

### Downloading the Dataset
Due to file size limitations, download the dataset separately from these official links:

- [Training Images (~263 MB)](https://benchmark.ini.rub.de/Dataset/GTSRB_Final_Training_Images.zip)  
- [Testing Images (~84 MB)](https://benchmark.ini.rub.de/Dataset/GTSRB_Final_Test_Images.zip)

Extract the downloaded ZIP files into your local workspace.

## Implementation Steps
- **Data Preparation:** Preprocessing, normalization, and splitting data into training and validation sets.
- **CNN Architecture:** Defining convolutional layers, pooling layers, activation functions, and fully connected layers.
- **Model Compilation:** Compiling the model with loss functions and optimization methods.
- **Training:** Training the CNN model, monitoring accuracy and loss.
- **Evaluation:** Assessing model performance using metrics like accuracy, confusion matrices, and classification reports.

## Libraries Used
- TensorFlow/Keras
- NumPy
- Matplotlib
- Scikit-learn (optional for evaluation metrics)

## Usage Instructions
1. Clone the repository:
   ```bash
   git clone [your-repo-url]
   ```
2. Install required libraries:
   ```bash
   pip install numpy matplotlib tensorflow scikit-learn
   ```
3. Run the provided CNN Python script:
   ```bash
   python cnn_model.py
   ```

## Results
The CNN achieved robust performance on the image dataset, demonstrating strong feature extraction and classification capabilities.

## Author
- **Pavia Bera**
- **Email:** paviabera@usf.edu

## License
Distributed under the MIT License. See `LICENSE` for more information.

