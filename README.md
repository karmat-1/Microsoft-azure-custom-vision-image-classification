# 🧠 Azure Custom Vision Image Classifier - Python & C# Versions

This project demonstrates how to use **Azure Custom Vision** to build an image classifier that can identify objects (like fruits 🍎Apple, 🍌Banana, and 🍊Orange) from images. It includes implementations in **Python** and **C# (.NET)**.

---

## 🚀 What it Entails
- How to connect to Azure’s Custom Vision Prediction API
- How to send images for classification and get predictions
- How to handle prediction responses in Python and C#
- Common issues and how to resolve them

---

## 🛠️ Prerequisites

### 🔑 Azure Setup
1. Create a Custom Vision project on the [Azure Custom Vision portal](https://www.customvision.ai/).
2. Train your model with labeled images and **publish** it.
3. Save the following values:
   - **Prediction Key**
   - **Endpoint URL**
   - **Project ID**
   - **Published Iteration Name**

---

## 🐍 Python Implementation

### 📁 Folder: `Python/`

### 📦 Install Requirements
```bash
pip install azure-cognitiveservices-vision-customvision
```
###🧪 Run the Classifier
```bash
python classify_images.py
```

## 💻 C# (.NET) Implementation

### 📁 Folder: C-Sharp/test-classifier/

### 📦 Install Required Package
```bash
dotnet add package Microsoft.Azure.CognitiveServices.Vision.CustomVision.Prediction
```
###🧪 Run the Classifier
```bash
dotnet run
```
