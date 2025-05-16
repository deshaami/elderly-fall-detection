# Elderly Fall Detection

A robust fall detection system for elderly individuals using deep learning and computer vision techniques.

---

## Project Summary

This project addresses the critical challenge of timely and accurate fall detection among elderly individuals, a key factor in reducing injury-related complications and improving quality of life.

The system combines state-of-the-art computer vision and deep learning techniques to analyze video and image data for real-time fall detection. Key innovations include:

- **Human Pose Estimation:** Utilizing YOLOv8 for precise localization of human keypoints to understand posture and movements indicative of falls.
- **Synthetic Data Generation:** To overcome limited real-world fall data, synthetic datasets were created using OpenPose for keypoint extraction and Generative Adversarial Networks (GANs) to augment training samples, improving model robustness and generalization.
- **Deep Learning Models:** Multiple models such as Convolutional Neural Networks (CNN), Support Vector Machines (SVM), and Logistic Regression were evaluated. The CNN model outperformed others, achieving a 97% accuracy in detecting falls.
- **Real-time Detection:** The integration of YOLOv8 allows for efficient, real-time processing suitable for deployment in healthcare monitoring systems.
- **Preprocessing and Feature Engineering:** The project involved extensive data preprocessing, including noise removal and feature extraction to enhance model performance.
- **Evaluation Metrics:** Comprehensive testing with precision, recall, and F1-score metrics ensured the system's reliability and minimized false alarms.

This work contributes to the field of healthcare AI by providing a scalable, accurate fall detection solution that can potentially be integrated into smart home or assisted living environments.

---

## Dataset

- Dataset collected and annotated using [Roboflow](https://roboflow.com/)  
- Included synthetic data augmentation generated with OpenPose and GANs to improve model robustness

---

## Methodology

- **Human Pose Estimation:** Utilized YOLOv8 for detecting human keypoints and posture  
- **Feature Extraction:** Employed CNN architectures for feature learning and classification  
- **Model Evaluation:** Achieved accuracy of 97% on the test dataset, outperforming baseline models like SVM and Logistic Regression

---

## Technologies Used

- Python, TensorFlow, PyTorch  
- YOLOv8, OpenPose, GANs  
- OpenCV for image processing  
- MATLAB Simulink for supplementary analysis

---

## Results

- High accuracy and low false positive rates in fall detection  
- Real-time performance suitable for healthcare monitoring systems

---

## Future Work

- Integration with wearable sensors for multi-modal detection  
- Deployment on edge devices for home-care monitoring

---

## Contact

For more details or collaboration opportunities, please contact:

**Aleena Roy**  
Email: aleenapallippadavil@gmail.com  
LinkedIn: [linkedin.com/in/aleena-roy-113b40230](https://www.linkedin.com/in/aleena-roy-113b40230)
