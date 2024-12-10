# Early Alzheimer's Detection Using CNNs

## Team Members
- **Brad Richardson**  
  Applied Computer Science, BS Post-Baccalaureate  
  University of Colorado Boulder  
  Email: brri6685@colorado.edu

## Description of the Project
This project investigates the application of deep learning for the early detection and staging of Alzheimer's disease using MRI brain images. Utilizing convolutional neural networks (CNNs) and the OASIS MRI dataset, the study aims to classify brain scans into four distinct categories:  
1. **Non-demented**  
2. **Very mild dementia**  
3. **Mild dementia**  
4. **Moderate dementia**

The project leverages transfer learning with the VGG16 architecture to identify subtle structural changes in the brain that correlate with disease progression, offering a novel approach to automated staging of Alzheimer’s.

## Summary of the Questions Sought and the Answers
### Research Questions:
1. **Can CNNs effectively classify Alzheimer's disease progression stages based on MRI scans?**  
   - **Answer:** The trained CNN achieved ~89% overall accuracy, demonstrating strong performance in distinguishing early stages like very mild dementia.  

2. **What are the challenges of multi-class classification in this context?**  
   - **Answer:** Class imbalance (e.g., moderate dementia representing only 0.56% of the data) and subtle anatomical differences posed significant challenges. Applying class weighting and Grad-CAM visualizations helped address these issues.

3. **Can visualizations provide clinical insights into the model’s predictions?**  
   - **Answer:** Grad-CAM highlighted regions such as the hippocampus, emphasizing their importance in early detection.

## Application of This Knowledge
The findings have multiple practical applications:
- **Clinical Decision Support:** Early detection tools for radiologists to identify subtle indicators of dementia.  
- **Patient Monitoring:** Tracking disease progression over time for personalized care.  
- **Clinical Trials:** Enhanced participant stratification based on disease stage.  
- **Resource Allocation:** Efficient prioritization of specialized care for high-risk patients.

## Link to the Video Demonstration
[**Watch the project video demonstration here.**](01_EarlyAlzheimersDetection_Part6_Video.mp4)

## Link to the Final Project Paper
[**Download the final project paper here.**](01_EarlyAlzheimersDetection_Part4.pdf)