# Mpox Identification Using Convolutional Neural Networks

## Project Overview
This project aims to assess the accuracy of Convolutional Neural Networks (CNNs) in classifying mpox virus from images. The study is motivated by the 2022 mpox outbreak, which was declared a global health emergency. We explore the efficacy of lightweight CNN models for potential integration into mobile applications, enhancing diagnostic capabilities globally.

## Methodology
- **Data Sources:** Utilized two publicly available datasets with additional data augmentation.
- **CNN Architectures:** Employed MobileNetV2 and Xception models with transfer learning. These were run in a Goolge Colab environment.
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
MobileNetV2 Architecture
![Xception Architecture](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_model_plot.png)
Xception Architecture

### Training Performance
![MobileNetV2 Training](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_Fine%20Tuning%20Accuracy%20%2B%20Loss%20Curves.png)
MobileNetV2 Training
![Xception Training](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_Fine%20Tuning%20Accuracy%20%2B%20Loss%20Curves.png)
Xception Training

### Evaluation Metrics
![MobileNetV2 Matrix](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_confusion%20matrix.png)
MobileNetV2 Matrix
![MobileNetV2 ROC Curve](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_AUC.png)
MobileNetV2 ROC Curve
![Xception Matrix](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_confusion%20matrix.png)
Xception Matrix
![Xception ROC Curve](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_AUC.png)
Xception ROC Curve