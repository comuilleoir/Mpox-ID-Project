# Mpox Identification Using Convolutional Neural Networks

## Project Overview
This project aims to assess the accuracy of Convolutional Neural Networks (CNNs) in classifying mpox virus from images. The study is motivated by the 2022 mpox outbreak, which was declared a global health emergency. We explore the efficacy of lightweight CNN models for potential integration into mobile applications, enhancing diagnostic capabilities globally.

## Methodology
- **Data Sources:** Utilized two publicly available datasets with additional data augmentation.
- **CNN Architectures:** Employed MobileNetV2 and Xception models with transfer learning.
- **Evaluation Metrics:** Focused on accuracy, precision, recall, and F1 scores.

## Key Findings
- The optimal results were obtained via transfer learning, achieving 89% accuracy.
- Comparable precision and recall scores in both MobileNetV2 and Xception architectures.

## Repository Contents
- `data`: Folder containing raw and processes image dataset.
- `scripts`: Source code for data preprocessing, model training, and evaluation scripts.

## Images and Visualizations

### CNN Architectures
![MobileNetV2 Architecture](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_model_plot.png)
![Xception Architecture](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_model_plot.png)

### Data Augmentation
![Data Augmentation Example](path/to/data_augmentation_example.png)

### Training Performance
![Training Accuracy Graph](path/to/training_accuracy_graph.png)
![Training Loss Graph](path/to/training_loss_graph.png)

### Evaluation Metrics
![Confusion Matrix](path/to/confusion_matrix.png)
![ROC Curve](path/to/roc_curve.png)

### Sample Predictions
![Sample Prediction 1](path/to/sample_prediction_1.png)
![Sample Prediction 2](path/to/sample_prediction_2.png)
