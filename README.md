# PaddyImage_classification

A project to classify paddy images as flooded or dry using an AI model built with Convolutional Neural Networks (CNN).

## Dataset Overview

The dataset consists of two main folders:

### Train folder
- **with_water**: Contains 100 images of paddy fields with water.
- **without_water**: Contains 100 images of paddy fields without water.

### Test folder
- **with_water**: Contains 8 images of paddy fields with water for validation.
- **without_water**: Contains 8 images of paddy fields without water for validation.

## Model Architecture

The CNN model architecture used for classification includes:
- Convolutional layers - 3(Feature Extraction)
- Pooling layers - 3(reducing number of parameters - less computation)
- Fully connected layers - 2(combine the features learned by the convolutional layers)
- Dropout regularization - 2(Avoids overfitting - 0.2)

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/your_username/PaddyImage_classification.git
   ```
   
2. Navigate to the project directory:
   ```
   cd PaddyImage_classification
   ```

3. Train and Test the model:
   ```
   Water_Classification.ipynb
   ```

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Results

The training and validation results obtained during model training are as follows:

Epoch 1/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 8s 734ms/step - accuracy: 0.4735 - loss: 1.6541 - val_accuracy: 0.5000 - val_loss: 0.6943
Epoch 2/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 630ms/step - accuracy: 0.5038 - loss: 0.7091 - val_accuracy: 0.1875 - val_loss: 0.6931
Epoch 3/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 653ms/step - accuracy: 0.6329 - loss: 0.6687 - val_accuracy: 0.6250 - val_loss: 0.6777
Epoch 4/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 652ms/step - accuracy: 0.7360 - loss: 0.5809 - val_accuracy: 0.8750 - val_loss: 0.5431
Epoch 5/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 661ms/step - accuracy: 0.7789 - loss: 0.5276 - val_accuracy: 0.9375 - val_loss: 0.3535
Epoch 6/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 667ms/step - accuracy: 0.8391 - loss: 0.3860 - val_accuracy: 1.0000 - val_loss: 0.2075
Epoch 7/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 645ms/step - accuracy: 0.8678 - loss: 0.3542 - val_accuracy: 0.9375 - val_loss: 0.2289
Epoch 8/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 660ms/step - accuracy: 0.8661 - loss: 0.3612 - val_accuracy: 0.8125 - val_loss: 0.4693
Epoch 9/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 647ms/step - accuracy: 0.8528 - loss: 0.3188 - val_accuracy: 0.8750 - val_loss: 0.2959
Epoch 10/10
7/7 ━━━━━━━━━━━━━━━━━━━━ 5s 667ms/step - accuracy: 0.8902 - loss: 0.2807 - val_accuracy: 1.0000 - val_loss: 0.2314

These results provide insights into the model's performance during training and validation epochs. 
Need to futher analyze and interpret these results to evaluate the effectiveness of your model. 
Update the paths and filenames according to your project.

