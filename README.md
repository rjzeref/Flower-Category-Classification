

---

# 🌸 Image-Based Dimension Extraction and Flower Classification using SFFFP Neural Network

## 🚀 Overview  
This project presents a novel approach to automate flower species identification and classification, focusing on tri-petal flowers like **Iris**. Leveraging **deep learning** with a **Sequential Fast Forward Feed Perceptron (SFFFP)** neural network, this method overcomes traditional challenges like manual feature extraction and dataset limitations. Achieving an impressive **96.67% precision accuracy**, the proposed system paves the way for robust and scalable image-based plant identification solutions.

---

## 🧠 Key Features  
- **Automated Dimension Extraction**: Measures sepal and petal dimensions from images using lightweight segmentation techniques.  
- **Real-World Scalability**: Converts pixel measurements to real-world dimensions (cm) through external calibration.  
- **High-Accuracy Classification**: Utilizes SFFFP for precise classification of Iris species (`Iris setosa`, `Iris versicolor`, `Iris virginica`).  
- **Minimal Preprocessing**: Eliminates the need for pre-measured datasets or manual feature extraction.  

---

## 📂 Dataset  
- Dataset used: [Iris Flower Dataset](https://www.kaggle.com/).  
- Preprocessing includes:  
  - Exploratory Data Analysis (EDA)  
  - Train-test split (80%-20%) for robust evaluation  

---

## ⚙️ Methodology  
1. **Image Segmentation**  
   - Extract the flower from the background using lightweight processing techniques.  
   - RGB channel decomposition and emphasis on the **Blue Plane** for improved visibility.  

2. **Dimension Calculation**  
   - Extract pixel measurements for sepals and petals.  
   - Apply scaling factors to derive real-world dimensions.  

3. **Classification**  
   - Input dimensions into the **SFFFP Neural Network**.  
   - Train the model with 150 epochs for optimal performance.  

---

## 📊 Results  
- **Precision Accuracy**: 96.67%  
- Visualized the **correlation matrix**, **numeric distribution**, and **workflow algorithms**.  

---

## 🛠️ Tools and Technologies  
- **Python**: Core programming language  
- **TensorFlow/Keras**: For building the SFFFP Neural Network  
- **OpenCV**: For image processing  
- **Pandas, NumPy, Matplotlib**: For data manipulation and visualization  

---

## 🖼️ Visual Insights  
1. **Sample Iris Flowers**  
   ![Iris Varieties](link-to-image)  

2. **Correlation Heatmap**  
   ![Heatmap](link-to-image)  

3. **Workflow Diagram**  
   ![Workflow](link-to-image)  

---

## 📚 Publications  
This project was presented at the **2nd International Conference on Sustainable Computing and Smart Systems (ICSCSS 2024)**, published in IEEE Xplore.  

**DOI**: [10.1109/ICSCSS60660.2024.10625013](https://doi.org/10.1109/ICSCSS60660.2024.10625013)  

---

## 👩‍💻 Contributors  
- **Roumo Kundu** | Amity Institute of Information Technology, Ranchi, India  
- **Swayam Gupta** | Amity Institute of Information Technology, Ranchi, India  
- **Mohan Kumar Dehury** | Amity Institute of Information Technology, Ranchi, India  
- **Tannisha Kundu** | Amity Institute of Information Technology, Ranchi, India  
- **Madhusudan Narayan** | Amity Business School, Ranchi, India  
- **Asit Kumar Mohapatra** | Dr. Shyama Prasad Mukherjee University, Ranchi, India  

---

## 📄 License  
This project is licensed under the **IEEE Open Access License**. For more details, refer to the [publication](https://doi.org/10.1109/ICSCSS60660.2024.10625013).  

---

## 🤝 Acknowledgments  
Special thanks to **Amity University Jharkhand** and **IEEE Xplore** for supporting and publishing this work.  

---

