# **Ensemble Model for Image Classification on CIFAR-10**  

This repository implements **image classification** on the **CIFAR-10 dataset** using an **ensemble of ResNet18 models**. The model is built with **PyTorch** and leverages **timm** for efficient training.  

### **🛠️ Setup & Requirements**  
The following dependencies were used:  
- **Python** 3.9  
- **PyTorch** 1.10.1 + CUDA 11.3  
- **Torchvision** 0.11.2 + CUDA 11.3  
- **timm** 0.9.2  

To install the required packages, run:  
```sh
pip install -r requirements.txt
```  

### **📊 Performance**  
The ensemble model achieved a **testing accuracy of 97.26%** on the CIFAR-10 dataset.  

### **🚀 Training the Model**  
To train the model, run:  
```sh
python train.py
```  

### **🎯 Testing the Model**  
To evaluate the model on test data, run:  
```sh
python test.py
```  

### **📂 Project Structure**  
```
ResNet-Ensemble-Model-CIFAR10/
│── datasets/         # Dataset handling and preprocessing
│── models/           # Model architecture definitions
│── utils/            # Helper functions
│── train.py          # Training script
│── test.py           # Testing script
│── requirements.txt  # List of dependencies
│── README.md         # Project documentation
```  

### **📬 Contact**  
For any questions or contributions, feel free to open an issue or reach out.  

---
