# Brain-Tumor-Detection-and-Analysis-using-GRADcam

This project focuses on classifying brain tumors using Convolutional Neural Networks (CNNs) built with TensorFlow. It also integrates **Grad-CAM (Gradient-weighted Class Activation Mapping)** to provide explainability by highlighting regions of an MRI image that the model considers important for classification.  

---

## Project Overview  

Brain tumor detection is critical for early diagnosis and treatment. This project automates the detection process by classifying MRI scans into four categories:  
1. **Glioma Tumor**  
2. **No Tumor**  
3. **Meningioma Tumor**  
4. **Pituitary Tumor**  

The pipeline includes:  
- **Data Preprocessing:** Images are resized and organized for training and testing.  
- **Model Training:** A CNN is trained to classify the tumor type.  
- **Explainability:** Grad-CAM is used to visualize key regions influencing predictions.  

---

## Results  

### Accuracy  
The CNN achieved **91% accuracy** on the testing dataset. Below is the confusion matrix:  

![Confusion Matrix](https://github.com/user-attachments/assets/0ea2fe47-4a8f-4f02-af21-a8d4b27ded38)

### Grad-CAM Explanation  
Grad-CAM was implemented to visualize model decisions. The highlighted regions show which parts of the MRI scan contributed most to the classification.  

Example visualization:  
![Grad-CAM Example](https://github.com/user-attachments/assets/4f46ab2c-6a75-4516-8e48-504a0b8c4d95)

---

## License  

This project is licensed under the MIT License.  
