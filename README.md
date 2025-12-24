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
<img width="1280" height="581" alt="{43D84944-4A9E-4ED7-9200-B0B1D1D484CF}" src="https://github.com/user-attachments/assets/46a0cbb4-a4bf-4e11-8830-101cfe752356" />


🔥 Confusion Matrix (Test Set)
<img width="803" height="712" alt="{4C305EEA-4C69-42AD-86E9-A8DDF294E2AD}" src="https://github.com/user-attachments/assets/d2daf010-20c4-4a19-9331-38a6402cb3b9" />


❌ Visual Error Analysis (misclassified images)
<img width="371" height="381" alt="{822DAD49-B292-46D6-84D8-D0E4013751E8}" src="https://github.com/user-attachments/assets/1d3f0422-7684-458d-951e-e0b6e68b7cd9" />
<img width="368" height="387" alt="{787DB527-5DBA-4165-962F-C23B28BFF217}" src="https://github.com/user-attachments/assets/8e4e60fc-5a78-4439-99ef-1abb6bbfc235" />
<img width="364" height="373" alt="{D69E62D2-BEA1-4CDC-81A2-B8B694AA0D2B}" src="https://github.com/user-attachments/assets/d219fd23-7c1e-4b38-94f6-098247739349" />


🖼️ Custom Image Prediction Gallery with confidence scores
<img width="1128" height="491" alt="{BC7B7848-9601-4104-99DA-2F710CB66F3C}" src="https://github.com/user-attachments/assets/9c188818-1f24-4cb9-887f-f9deb5da3f53" />


Example prediction format:
- Fully Connected (Dense) layers
- Dropout for regularization
- Softmax output layer for classification

```text
Input Image (128×128×3)
→ Conv → ReLU → MaxPool
→ Conv → ReLU → MaxPool
→ Conv → ReLU → MaxPool
→ Fully Connected → Output (10 classes)




