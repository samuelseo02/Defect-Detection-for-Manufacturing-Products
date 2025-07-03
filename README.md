#  Defect Detection for Manufacturing Products

A computer vision project using a CNN and transfer learning to detect subtle defects in manufactured products. Developed collaboratively as part of a machine learning and computer vision module (June 2024).

---

##  My Contributions
- Preprocessed image data (normalization, augmentation, resizing)  
- Handled GPU configuration and debugging in a Colab environment  

---

##  Dataset
- Source: [MVTec Anomaly Detection Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad)  
- Includes ~5,000 high-resolution images of various industrial objects with labeled defects  
- Preprocessing included resizing to 224x224 and augmentation (flip, zoom, brightness)  
- Balanced dataset using augmentation and stratified sampling  

---

##  Evaluation & Environment
- Model: Pre-trained CNN (e.g. ResNet or MobileNet) with transfer learning  
- Achieved **>10% accuracy improvement** over benchmark  
- Evaluation: Confusion matrix, training/validation loss plots  
- Tools: Google Colab with Tesla T4 GPU, Flask for the user interface  

---

##  Future Improvements
- Increase dataset size and diversity (e.g. lighting conditions, camera angles)  
- Add explainable AI tools like Grad-CAM to visualise decision areas  
- Deploy the web app using Heroku, Render, or similar hosting platforms  
- Extend model for multi-class classification to identify defect types  
- Add monitoring features to track model accuracy drift in real-world deployment
