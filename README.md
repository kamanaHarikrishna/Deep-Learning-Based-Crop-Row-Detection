# Deep Learning-Based Crop Row Detection  
**🏆 Secured 3rd Place in the Purdue University Deep Learning Challenge 2024**  

## 📌 Project Overview  
This project focuses on **real-time crop row detection** using a **U-Net-based deep learning model** to enhance **precision agriculture**. The model classifies pixels as **crop rows or background**, improving autonomous farming operations.  

## 🔍 Problem Statement  
Traditional crop row detection methods struggle due to:  
- **Varying field conditions** (lighting, weed density, crop growth stages).  
- **Lack of large labeled datasets** for training robust deep learning models.  
- **Need for real-time, high-accuracy segmentation** to enable autonomous farming vehicles.  

## 🏆 Achievements  
- **Ranked 3rd** out of 80 teams at Purdue University’s **Deep Learning Challenge 2024**.  
- Developed an optimized **U-Net-based crop row detection model** for real-time precision agriculture.  
- Improved **segmentation accuracy and model efficiency** using advanced data processing techniques.  

## 🚀 Key Features  
✅ **U-Net Architecture**: Implemented with **skip connections** for enhanced semantic segmentation.  
✅ **Efficient Data Processing**: Converted **320x240 RGB images** into **numpy arrays**, ensuring proper preprocessing.  
✅ **Data Augmentation**: Applied **random flipping & rotation** to improve generalization.  
✅ **Optimized Training Process**: Used **Dice Loss** instead of Cross-Entropy Loss for better segmentation accuracy.  
✅ **Performance Metrics**: Evaluated with **mean Intersection over Union (mIoU) & Dice Coefficient** for high accuracy.  
✅ **Real-time Processing**: Designed to work efficiently in real-world agricultural environments.  

## 🔧 Technologies Used  
- **Deep Learning Frameworks**: TensorFlow, PyTorch  
- **Machine Learning Libraries**: OpenCV, Scikit-learn  
- **Programming Language**: Python  
- **Data Processing**: NumPy, Pandas  
- **Evaluation Metrics**: mIoU, Dice Coefficient  

## 📊 Results  
- **High-precision crop row detection** with improved segmentation accuracy.  
- **Enhanced autonomous vehicle navigation** in farming fields.  
- **Reduction in manual labor dependency**, improving agricultural efficiency.  

## 📁 Dataset  
The dataset consists of **RGB images (320x240 resolution)**, with labeled crop row masks.  
- **Training Set:** 80%  
- **Validation Set:** 20%  

## 📥 How to Run the Project  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/deep-learning-crop-row-detection.git
   cd deep-learning-crop-row-detection
📜 Future Enhancements
Expand dataset with more diverse crop types and environments.
Integrate real-time video processing for continuous monitoring.
Deploy the model using edge computing for on-field processing.
📌 Contributors
[Hari Krishna kamana] - GitHub Profile
Purdue University Deep Learning Challenge Team
🎯 Connect
📧 Email: your-harikrishnausa9110@gmail.com
🌐 LinkedIn: www.linkedin.com/in/hari-krishna-kamana
