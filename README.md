# Pneumonia-Classifier

This repository contains a pneumonia detection application built using Convolutional Neural Networks (CNN) and deployed with Streamlit. Users can upload chest X-ray images to classify them as "Pneumonia" or "Normal," with real-time results displayed alongside confidence scores.  

### Features  
- **User Interface:** A Streamlit-based UI for uploading and visualizing chest X-ray images.  
- **Model:** Utilizes a pre-trained CNN model (`pneumonia_classifier.h5`) for classification, achieving high accuracy.  
- **Custom Background:** Implements a visually appealing background using Streamlit's style customization.  
- **Real-time Classification:** Outputs classification results and confidence scores instantly.  

### Files  
- `main.py`: The main Streamlit app handling file uploads, model loading, and displaying results.  
- `util.py`: Utility functions for background setup and image preprocessing for model inference.  
- `pneumonia_classifier.h5`: The pre-trained CNN model for pneumonia detection.  

### How to Use  
1. Clone the repository and set up the required environment.  
2. Run the `main.py` file to start the Streamlit app.  
3. Upload a chest X-ray image to receive classification results in real-time.  
