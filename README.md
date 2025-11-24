# 🛥️ Unauthorized Fishing Activity Tracker  
### *Deep Learning–Based Ship Detection Using Satellite Imagery*

This project detects ships in satellite images using **Convolutional Neural Networks (CNNs)** to help combat **illegal fishing** and improve maritime surveillance. By analyzing satellite imagery and generating prediction scores, the system identifies the presence of vessels that may be operating without authorization.

## 📌 Features
- 🚢 Ship detection using a trained CNN model  
- 🧠 Deep Learning pipeline with TensorFlow/Keras  
- 🖼️ Image preprocessing + augmentation  
- 💻 Streamlit web interface for real-time image prediction  
- 📊 Model evaluation with accuracy, precision, recall, F1-score  
- 💾 Saved models for inference  
- 🌍 Application for marine conservation & illegal fishing detection  

## 📂 Project Structure
```
.
├── model.py                
├── model2.py              
├── streamlit_app.py        
├── dataset/
│   ├── ship/
│   └── no_ship/
├── saved_models/
├── README.md
└── requirements.txt
```

## 🛠️ Technologies Used
Python, TensorFlow, Keras, NumPy, Pandas, Pillow, Scikit-learn, Streamlit, Matplotlib

## 📥 Dataset
The dataset includes **satellite images** labeled into `ship` and `no_ship`.

## ⚙️ Installation
```
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## 🤖 Model Overview
CNN architecture with convolutional layers, pooling, dense layers, dropout, and Adam/RMSProp optimizers.

## 🧪 Training & Evaluation
Includes augmentation, validation, confusion matrix, and metric evaluation.

## 🌐 Streamlit Web App
Upload an image → Get prediction → Probability score.

## 🚀 Future Enhancements
Real-time satellite feeds, global scaling, automated reporting, environmental assessment.

## 👥 Contributors
Supriya Priyadarshi  
Amritansh Kumar Verma  
Nabeel Anwar Siddiqui  
Sanjana Subudhi

Guide: Mr. Sourav Kumar Giri
