# CIFAR-10 Image Classification with CNN Experiments
This repository contains a deep learning project focused on image classification using the CIFAR-10 dataset. The objective was to train and compare 10 different model configurations, analyze their behavior, and improve performance through architectural changes, regularization strategies, optimizer tuning, and data augmentation.
More information: https://www.cs.toronto.edu/~kriz/cifar.html 

## Project overview
The project uses the CIFAR-10 dataset, which contains 50,000 training images and 10,000 test images. Each image is 32x32 pixels in RGB format and belongs to one of 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Objective
The main goals of the project were:
- Train and evaluate **10 different CNN-based configurations**
- Analyze performance improvements or degradations across experiments
- Reach at least **80% test accuracy**
- Compare the results of all models

## Methodology
Starting from a baseline CNN model, I iteratively tested different changes, including:
- Additional dense and convolutional layers
- Batch normalization
- Dropout regularization
- Optimizer changes (Adam and SGD)
- Learning rate and momentum tuning
- Batch size adjustments
- ReduceLROnPlateau
- Data augmentation

## Results
The best-performing model (*model  10*) achieved **80.79% test accuracy**, meeting the project target.

### Best model
Key improvements in the final model included:
- Data augmentation
- Adam optimizer
- Batch size = 256
- Reduced dropout in the dense stage

### Main conclusion
The experiments showed that increasing model complexity alone was not enough. The best results came from combining a solid architecture with regularization and data augmentation, which improved generalization and reduced the gap between training and test performance.

## Files
- `SaraRodriguez_CIFAR10_CNN.pdf` → full project report

## Author
Sara Rodríguez Portal
