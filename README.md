# 🍎🍌🍊 CNN Fruits Classification using PyTorch

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify **10 types of fresh fruits**.  
The model is trained on a structured image dataset and tested on **real-world custom images** taken separately and stored in the repository.

The entire workflow is **fully automated** and **Google Colab–ready**.

---

## 📌 Project Objectives

- Build a complete **CNN image classification pipeline**
- Train the model on a **standard fruit image dataset**
- Test the trained model on **custom real-world images**
- Ensure **reproducibility** using GitHub and Google Colab
- Visualize performance using plots and confusion matrix

---

## 🍓 Fruit Classes (10)

The model classifies the following fruit categories:

- Apple  
- Avocado  
- Banana  
- Cherry  
- Kiwi  
- Mango  
- Orange  
- Pineapple  
- Strawberries  
- (Other fruit class if present in dataset)

---

---

## ⚙️ Technologies Used

- **Python**
- **PyTorch**
- **Torchvision**
- **Google Colab**
- **Matplotlib**
- **Seaborn**
- **scikit-learn**
- **GitHub**

---

## 🧠 Model Architecture

The CNN architecture consists of:

- 3 Convolutional layers (`Conv2D`)
- ReLU activation functions
- Max Pooling layers

  🚀 How to Run (Google Colab)

Open Google Colab

Upload or open ID.ipynb

Click Runtime → Run all

The notebook will automatically:

Clone this GitHub repository

Load the dataset

Train the CNN model

Save the trained model (.pth)

Evaluate performance

Predict custom fruit images

✅ No manual file upload required
📊 Results & Visualizations

The notebook generates:

📈 Training Loss vs Epoch plot                                                                                                   📈 Training Accuracy vs Epoch plot
<img width="1443" height="525" alt="{F3CAA496-6A94-4B0A-8C18-B89C8A005A72}" src="https://github.com/user-attachments/assets/1796a8f3-283e-45a0-b043-adc7bfcb9378" />




🔥 Confusion Matrix (Test Set)
<img width="1202" height="764" alt="{CB0B6F37-81BD-49DC-881D-3C24C27D92BF}" src="https://github.com/user-attachments/assets/e147bdb5-ff09-49dc-9196-d9d46f45f379" />



❌ Visual Error Analysis (misclassified images)
<img width="417" height="341" alt="{9ABE4F73-BDB6-44ED-ACE2-44F269566B12}" src="https://github.com/user-attachments/assets/926815fc-ac35-481c-8a0f-2e9f3a44be2d" />
<img width="408" height="340" alt="{9ED66DA9-0DF8-445B-BAC7-144329B1A439}" src="https://github.com/user-attachments/assets/5c9d4a14-bb55-44c6-9885-d66a24e63dfe" />
<img width="452" height="281" alt="{251233A5-1154-476B-933E-F186B9F5BFAF}" src="https://github.com/user-attachments/assets/5f83667e-16c7-4b7b-a111-b7c638ab2fcb" />



🖼️ Custom Image Prediction Gallery with confidence scores
<img width="1311" height="738" alt="{4CC15C8B-B416-40D6-A2E5-03EFAF9CA29E}" src="https://github.com/user-attachments/assets/aefc85aa-8e94-4484-a2c5-7b2c6e07c9ad" />














