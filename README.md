# 🫑 Bell Pepper Plant Disease Detection

This repository contains the code and experiments for a Computer Vision project aimed at detecting and classifying diseases in bell pepper plants. The system processes images of **bell pepper leaves** and **bell pepper fruits** to identify whether the plant is healthy or infected with a specific disease.

## 📂 Dataset Access

Due to the massive size of the image dataset (in GBs) which exceeds GitHub's file size limits, the image dataset is **not included** in this repository. 

You can download the complete dataset separately via the Google Drive link below:

🔗 **[Download Bell Pepper Plant Disease Dataset (Google Drive)](https://drive.google.com/drive/folders/1nqHdf2o4mb60beFq8TIscWvsLLodgY1d?usp=sharing)**

**How to Use the Dataset:**
1. Download the folder/ZIP file from the link above.
2. Extract the file (if downloaded as a ZIP).
3. Place the dataset folder into your local directory (e.g., in a `dataset/` folder at the root of this project, or in your Google Drive directory if using Google Colab).

## 🏷️ Disease Classes

The AI model in this project is trained to recognize a total of 9 classes, which are divided into two main object categories:

### 1. Bell Pepper Fruit
- **Bell Pepper Healthy**
- **Bell Pepper Rotten**

### 2. Bell Pepper Leaf
- **Leaf Blight**
- **Mosaic**
- **Leaf Curl**
- **Bacterial Spot**
- **Fusarium**
- **Septoria**
- **Healthy**

## 🚀 Installation & Setup

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
