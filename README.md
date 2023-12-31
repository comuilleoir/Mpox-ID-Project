# Mpox Identification Using Convolutional Neural Networks

## Project Overview
This project aims to assess the accuracy of Convolutional Neural Networks (CNNs) in classifying mpox virus from images. The study is motivated by the 2022 mpox outbreak, which was declared a global health emergency. We explore the efficacy of lightweight CNN models for potential integration into mobile applications, enhancing diagnostic capabilities globally.

## Methodology
- **Data Sources:** Two publicly available datasets containing images of mpox lesions were used.
- **Data Preprocessing:** Data was preprocessed for optimal performance, including rescaling pixel values.
- **Models Used:** MobileNet and Xception models were employed, known for efficiency in image classification tasks.
  - **MobileNet Customization:** Custom layers were added for specific mpox identification requirements.
  - **Xception Customization:** Adapted for fine-grained image details.
- **Image Processing Techniques:** Advanced techniques were applied to enhance diagnostic feature discernment.
- **Evaluation Metrics:** Focused on accuracy, precision, recall, and F1 scores.

## Results and Observations
- **Performance Metrics:** Achieved an 89% accuracy with comparable precision and recall scores in both MobileNetV2 and Xception models.
- **Model Comparison:** Insights into MobileNet and Xception performance in accuracy, speed, and resource consumption.

## Technologies Used
- **Python**: For scripting, data preprocessing, and model implementation.
- **MobileNet and Xception CNNs**: For image classification tasks, chosen for their efficiency and accuracy.
- **Data Augmentation and Preprocessing Tools**: To enhance the dataset and improve model training.

## Repository Contents
- `data`: Folder containing raw and processes image dataset.
- `scripts`: Source code for data preprocessing, model training, and evaluation scripts.
- `Project Images`: Features charts and plots such as AUC and confusion matrices, providing insights from the analysis.

## Images and Visualizations

### CNN Architectures
MobileNetV2 Architecture

![MobileNetV2 Architecture](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_model_plot.png)

Xception Architecture

![Xception Architecture](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_model_plot.png)


### Training Performance
MobileNetV2 Training

![MobileNetV2 Training](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_Fine%20Tuning%20Accuracy%20%2B%20Loss%20Curves.png)

Xception Training

![Xception Training](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_Fine%20Tuning%20Accuracy%20%2B%20Loss%20Curves.png)


### Evaluation Metrics
MobileNetV2 Matrix

![MobileNetV2 Matrix](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_confusion%20matrix.png)

MobileNetV2 ROC Curve

![MobileNetV2 ROC Curve](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Mobilenet_AUC.png)

Xception Matrix

![Xception Matrix](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_confusion%20matrix.png)

Xception ROC Curve

![Xception ROC Curve](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Xception_AUC.png)

### Evaluation Metrics
State of Art Comparison

![State of Art Comparison](https://github.com/comuilleoir/Mpox-ID-Project/blob/main/Project%20Images/Camparison%20To%20State%20of%20Art.png)

## Limitations and Future Work
- **Data Availability**: Limited by the volume of publicly available mpox image data.
- **Future Directions**: Suggests exploration of additional CNN architectures and further data augmentation techniques to improve classification accuracy. Potential for extending the study to multi-class classification of various skin conditions.