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
- `data`: Folder containing dataset samples and augmentation details.
- `models`: Trained model files and architecture details.
- `notebooks`: Jupyter notebooks with model training and evaluation steps.
- `src`: Source code for data preprocessing, model training, and evaluation scripts.

## Installation and Usage
Instructions on how to set up the environment, install dependencies, and run the project.

## Contributing
Guidelines for contributing to the project, including coding standards and pull request process.

## License
Details of the project license.

## Contact Information
- Deirdre O'Regan - `x19175361@student.ncirl.ie`
- Cian Ó Muilleoir - `x20144717@student.ncirl.ie`
- Conor Moody - `x21201765@student.ncirl.ie`
- Stephen Greene - `x20153171@student.ncirl.ie`

## Images and Visualizations

### CNN Architectures
![MobileNetV2 Architecture](path/to/mobilenetv2_architecture.png)
![Xception Architecture](path/to/xception_architecture.png)

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
