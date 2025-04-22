# 🚦 Traffic Congestion Prediction using Machine Learning  

### **📌 Overview**  
This project predicts **traffic congestion levels** (High, Medium, Low) using **sensor data** such as vehicle speed, sensor count, and time of day. The model is trained using **Random Forest Classifier**, achieving an accuracy of ~85% in classifying congestion.  

### **🔍 Problem Statement**  
Urban traffic congestion affects millions daily. This AI-based solution helps traffic authorities **optimize flow, reduce delays, and improve commuter experiences** by providing **real-time congestion predictions** based on sensor data.  

### **🎯 Objectives**  
✅ Preprocess traffic sensor data for training  
✅ Train a **Random Forest classifier** for congestion prediction  
✅ Evaluate model accuracy & visualize trends using **heatmaps & scatter plots**  
✅ Make real-time predictions from **user inputs**  

### **📂 Dataset Features**  
| Feature | Description |
|---------|------------|
| **sensor_count** | Number of traffic sensors detecting vehicle movement |
| **avg_speed** | Speed of vehicles in a section |
| **time_of_day** | Categorical (morning, afternoon, evening, night) |
| **congestion_level** | Target label (High, Medium, Low) |

### **🛠 Tech Stack**  
🔹 **Python** (pandas, numpy, sklearn, seaborn, matplotlib)  
🔹 **Machine Learning** (Random Forest Classifier)  
🔹 **Google Colab** (Dataset processing & training)  

### **📊 Visualizations**  
✔ **Heatmaps** to analyze feature correlations  
✔ **Scatter plots** showing congestion trends  
✔ **Confusion matrix heatmap** for model evaluation  

### **🚀 How to Use**  
1️⃣ Clone this repository  
2️⃣ Upload the CSV dataset in **Google Drive**  
3️⃣ Run the Colab notebook to train the model  
4️⃣ Enter sensor data (count, speed, time of day)  
5️⃣ Get real-time **congestion level predictions**  

### **🔗 References**  
📌 scikit-learn documentation  
📌 pandas & seaborn for data visualization  
📌 Research articles on smart traffic analytics  

### **💡 Future Improvements**  
🔹 **Integrate weather conditions** for better accuracy  
🔹 **Expand dataset** to include holiday/weekend effects  
🔹 **Use deep learning models** like LSTM for traffic forecasting 
