# 🛰️ Infrastructure Change Detection Using Satellite Imagery  

![image](https://github.com/user-attachments/assets/06abad8b-4067-4b96-9f57-d21493aca918)  

## 👨‍💻 Team 117  
**Guide:** MD. Sallaudin Sir  

| Name | Roll Number |
|------|------------|
| **THIPPANI VENKATA NAGASHESHU MANI** | 2103A52036 |
| **UGGE REETHUVARMA** | 2103A52038 |
| **SATTU SAI PRANEETH** | 2103A52034 |

---

## 📥 Download Dataset  
[📌 LEVIR-CD Dataset](https://drive.google.com/drive/folders/18yRibtppG78SHVotjgCp-VFeC062oMW2?usp=drive_link)  

The **LEVIR-CD dataset** is a **large-scale, high-resolution** collection of satellite images specifically designed for **building change detection tasks**.  

### 📊 Dataset Highlights  
✔️ **High-Resolution Data** – 637 image pairs of **1024 × 1024 pixels** at **0.5m per pixel resolution**  
✔️ **Building Change Focus** – Captures **construction** and **demolition** over **5 to 14 years**  

![image](https://github.com/user-attachments/assets/e5c34116-ec38-4b82-9a6b-378afa0314ff)  

---

## 🏗️ Model Architecture  
The **Siamese U-Net** consists of two **parallel U-Net branches** with shared weights, designed to efficiently compare two input images and detect structural changes.  

### **🔹 Architecture Diagram**  
![image 1](https://github.com/user-attachments/assets/f4dcac64-52ef-4350-a0ec-a7f48b29493c)  

---

## 📊 Results  
The model was evaluated on **high-resolution satellite images**, successfully detecting infrastructure changes with precision.  

### **🔹 Sample Outputs**  
**Detected Changes on Real Satellite Data**  
![image 2](https://github.com/user-attachments/assets/af131de6-8e82-4379-b670-94af99715bd0)  

**More Results**  
![image 3](https://github.com/user-attachments/assets/36151e94-0fa4-438d-bf48-47d79ffc0bc3)  

**Example of Processed Image with Segmentation Mask**  
![__results___7_0](https://github.com/user-attachments/assets/464a104a-d7ef-4fa1-91fc-af97312433b4)  

---
