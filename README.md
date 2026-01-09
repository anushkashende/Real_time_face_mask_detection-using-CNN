# 🟢 Real-Time Face Mask Detection Using CNN

---

## 📄 Project Overview
This project detects whether a person is wearing a **face mask** in real-time using a **Convolutional Neural Network (CNN)**.  
It is designed to work with a webcam and provides high accuracy for masked and unmasked faces.

---

## 🎯 Objectives
- Develop a real-time face mask detection system.  
- Train a CNN model on a dataset of masked and unmasked faces.  
- Deploy the model for live detection using a webcam.  
- Ensure high accuracy and performance suitable for real-time applications.  

---

## 🧠 Approach
1. **Data Collection:** Use a dataset of face images with and without masks.  
2. **Data Preprocessing:** Resize images, normalize pixel values, and augment data to improve model generalization.  
3. **Model Building:** Construct a CNN with multiple convolutional, pooling, and dense layers for classification.  
4. **Training:** Train the CNN on the dataset and save the model (`.h5` file).  
5. **Real-Time Detection:** Load the trained model and detect masks in live webcam feed using OpenCV.  

---

## 🗃 Dataset
Source: Kaggle

Dataset is too large for GitHub.  
Download from Google Drive: 
https://drive.google.com/file/d/1DOxY1hFvdFre9VLM6BULC9LoCY-kayXP/view?usp=sharing



## 🧠 Trained Model
Pre-trained CNN model (.h5): 
https://drive.google.com/file/d/1SnaOWX3VdDXIh5mNIfGa5lQ6dcT4kwQ5/view?usp=sharing



---

## 🔄 Project Flow
1. Load and preprocess the dataset.  
2. Build the CNN model architecture.  
3. Train the model and save it as `face_mask_detector_model.h5`.  
4. Run `real_time_mask_detection.py` to detect masks using webcam.  

---

## 📊 Model Evaluation
- Accuracy on training dataset: ~99%  
- Accuracy on validation dataset: ~99%  
- Loss: very low, indicating a well-trained model.  
- Model can be retrained with new datasets if required.  

---

## 💻 Technology Used
- **Programming Language:** Python 3.x  
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy  
- **IDE/Platform:** VS Code, Python environment  

---

## ▶ How to Run

# 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```


# 2️⃣ Train the Model (Optional)

If you want to train the CNN model yourself:

```bash
python train_model.py
```

# 3️⃣ Run Real-Time Mask Detection

```bash
python real_time_mask_detection.py
```

# 🚀 Future Enhancements

Add detection for improper mask usage (mask worn incorrectly).

Extend to multiple faces in the frame simultaneously.

Convert model to TensorFlow Lite for mobile deployment.

Add notification system for workplaces or public spaces.

# 📝 Author

~Group B

Anushka Shende 

Krishika Agarwal 

Nandeshwar Parate 

Satyam Kumar 

Pushpak Telrandhe 

Prerna Bhande 

Neel Rathi 

Vedika Warade 

Shweta Pandhare 


# 🙏 Acknowledgments

Open-source contributions for TensorFlow, Keras, and OpenCV libraries

Dataset contributors for mask and no-mask images







