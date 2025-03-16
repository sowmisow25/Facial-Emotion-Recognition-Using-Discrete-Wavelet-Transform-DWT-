<div align="center">

# Facial Emotion Recognition Using Discrete Wavelet Transform (DWT) 😃😡😢  

</div>

Welcome to the **Facial Emotion Recognition Using DWT** project! This was my **MTech final year project**, where I combined advanced image processing techniques with deep learning models to classify human facial emotions into seven distinct categories. Using **Discrete Wavelet Transform (DWT)** for feature extraction and training models like **MobileNet**, **AlexNet**, and **GoogleNet**, the project achieved enhanced accuracy and robustness in emotion detection.


## **Objective**  

To classify facial expressions into seven emotions—**Happy, Sad, Angry, Neutral, Surprise, Disgust, Fear**—by integrating **wavelet transformation (DWT)** for feature extraction and applying deep learning models to improve classification accuracy.  


## **Introduction**  

Facial emotion recognition has become an essential component of AI-driven applications such as human-computer interaction, security systems, and healthcare monitoring.  
This project addresses limitations in existing systems by leveraging **DWT** to decompose facial images into frequency sub-bands, providing a richer feature set for deep learning models. Models like **MobileNet**, **AlexNet**, and **GoogleNet** were trained to classify emotions with high accuracy, with MobileNet emerging as the most effective model.  


## **Workflow**  

### **1. Data Collection**  
- **Dataset Used**: Kaggle's facial expression dataset.  
- **Categories**: Seven distinct emotions (*Happy, Sad, Angry, Neutral, Surprise, Disgust, Fear*).  

### **2. Preprocessing**  
- Noise removal and normalization of images for better model input.  
- Resizing images to fixed dimensions for model compatibility.  
- Applied **data augmentation techniques** like rotation, flipping, and cropping to increase dataset robustness.  

### **3. Feature Extraction Using DWT**  
- Images were decomposed into frequency sub-bands using **Discrete Wavelet Transform (DWT)**.  
- The DWT coefficients were passed as inputs to the deep learning models, providing enhanced features for classification.  

### **4. Model Training**  
- Trained the following deep learning models:  
  - **CNN (Convolutional Neural Network)**  
  - **MobileNet**  
  - **AlexNet**  
  - **GoogleNet**  
- Used **PyCharm IDE** for coding, training, and testing models.  
- Split the dataset into **training** (80%) and **testing** (20%) sets for evaluation.  

### **5. Emotion Classification**  
- Models were tested on unseen data to classify emotions.  
- Among all models, **MobileNet integrated with DWT** delivered the best classification performance.  


## **Technologies Used**  

- **Programming Language**: Python.  
- **Deep Learning Frameworks**: TensorFlow, Keras.  
- **Image Processing**: Discrete Wavelet Transform (DWT).  
- **Development Environment**: PyCharm IDE.  


## **Key Results**  

- **Best Model**: MobileNet with DWT.  
- **Performance Metrics**:  
  - Achieved higher classification accuracy than models without DWT.  
  - DWT improved feature visualization and reduced misclassification rates.  
- Successfully classified all seven emotions across diverse facial expressions.  


## **Applications**  

- **Human-Computer Interaction**: Enhancing systems with emotion-aware interfaces.  
- **Security Systems**: Real-time monitoring of suspicious behaviors.  
- **Healthcare**: Emotion tracking for mental health and patient well-being.  


## **Challenges Faced**  

1. Preprocessing large datasets required significant computational resources.  
2. Fine-tuning deep learning models for optimal accuracy took several iterations.  
3. Handling imbalanced data across emotion categories required augmentation techniques.  


## **Project Impact**  

This project demonstrated the power of combining **image processing** with deep learning models to improve emotion classification. The insights and techniques used in this project can help develop robust systems for real-world applications.  


## **Further Improvements**  

- Use larger, more diverse datasets for better generalization.  
- Implement real-time emotion recognition for video feeds.  
- Experiment with transfer learning for improved accuracy.  


## **References**  

- Kaggle Facial Expression Dataset  
- Research Paper: Images Attached  


## **Stay Connected**  

You can connect with me on:  
- [LinkedIn](https://www.linkedin.com/in/sowmya-sreenivasan/)  
- [GitHub](https://github.com/sowmyasreenivasan)  

## **Note**  
The code file and related details could not be uploaded to this repository as the file size exceeds GitHub's upload limit. I attempted to upload the file but was restricted due to its large size. Thank you for understanding! If you'd like more information about the code or the project, feel free to reach out to me.


