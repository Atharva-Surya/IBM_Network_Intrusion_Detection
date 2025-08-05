# IBM_Network_Intrusion_Detection

# Efficient Network Intrusion Detection via AutoAI Pipelines on IBM Cloud

## 📌 Project Overview

This project presents a **Network Intrusion Detection System (NIDS)** powered by **IBM watsonx.ai's AutoAI** capabilities. The goal is to automatically detect and classify suspicious network activity in real-time, improving network security through intelligent automation and cloud deployment.

> 🚀 Developed by: **Atharva Vijay Suryawanshi**  
> 🏫 MIT Academy of Engineering, Pune  
> 👨‍💻 Department of Computer Engineering  

---

## 🧠 Problem Statement

Modern digital networks face threats like **Denial-of-Service (DoS)** attacks, probing, unauthorized access, and more. Traditional rule-based systems often fail to detect novel or sophisticated threats. There is a need for an intelligent, real-time, automated solution to **analyze network traffic** and **detect intrusions** with minimal human intervention.

---

## ✅ Proposed Solution

The proposed system:

- Uses **AutoAI on IBM watsonx.ai** to build, train, and optimize ML pipelines.
- Classifies incoming traffic as **normal** or **malicious**.
- Deploys the best-performing model as a **REST API endpoint** on IBM Cloud.
- Continuously monitors model accuracy and performance.

---

## 🛠️ System Development Approach

1. **Data Collection**
   - Used public network intrusion datasets (e.g., **NSL-KDD / KDD’99**) from [Kaggle](https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection).
2. **Data Preprocessing**
   - Handled missing values, encoded categorical features, and normalized numeric attributes using AutoAI.
3. **Model Generation & Selection**
   - AutoAI automatically tested various ML models (e.g., Snap Decision Tree, Random Forest).
   - Best-performing pipeline selected based on metrics like **Accuracy**, **Precision**, **Recall**, and **F1-score**.
4. **Deployment**
   - Top model deployed as a **REST API** on IBM Cloud using Watson Machine Learning.
<img width="1919" height="850" alt="Screenshot 2025-08-03 214323" src="https://github.com/user-attachments/assets/dd146a78-8d58-4edc-bf18-b9bfb36ac51b" />

---

## 🧪 Results

- Achieved **100% classification confidence** on the test dataset.
- Successfully classified network connections as either **normal** or **intrusions** across multiple test scenarios.
- Visual dashboards verified the accuracy of anomaly detection.

---<img width="1777" height="754" alt="Screenshot 2025-08-03 221433" src="https://github.com/user-attachments/assets/2e0f4d84-bef1-41d5-922d-b62a0b8c8821" />


## 📦 System Requirements

- **Dataset**: NSL-KDD / KDD’99 intrusion datasets
- **Platform**: IBM watsonx.ai Studio (IBM Cloud)
- **Access**: Web-based UI for pipeline configuration and predictions
- **Hardware**: Runs on IBM Cloud—no local compute needed

---

## 📈 Algorithms Used

- **Snap Decision Tree Classifier** (from IBM Snap ML)
- **AutoAI Pipeline Optimizer**
- Hyperparameter tuning and feature engineering done automatically

---

## 📍 Future Scope

- Integration with live-streamed network data.
- Enhancing robustness by testing on more diverse datasets.
- Real-world deployment in enterprise environments.

---

## 📚 References

- 📄 NSL-KDD Dataset: [Kaggle](https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection)
- 📘 IBM AutoAI Documentation: [AutoAI Docs](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/autoai.html)
- 📘 IBM watsonx.ai Documentation: [IBM Docs](https://www.ibm.com/docs/en/watsonx)
- 📘 IBM Cloud Object Storage: [IBM Cloud](https://cloud.ibm.com/docs/cloud-object-storage)

---

## 🏅 Certifications

This project was completed under the **IBM SkillsBuild** program with relevant certifications in:
- Journet To Cloud
<img width="1181" height="889" alt="Screenshot 2025-08-03 234811" src="https://github.com/user-attachments/assets/2707cd22-6602-44ba-b0b3-5c491d56fbba" />

- Getting Started With Artificial Intelligence
<img width="1187" height="886" alt="Screenshot 2025-08-03 234746" src="https://github.com/user-attachments/assets/c0c044ef-92fc-4116-80ea-41ca9ae4a861" />

  
- Lab: RAG with Langchain
  <img width="1117" height="727" alt="Screenshot 2025-08-03 234640" src="https://github.com/user-attachments/assets/b5ac7b43-5227-4920-9692-96ad304edae2" />

- Intro to RAG Lab
  <img width="948" height="626" alt="image" src="https://github.com/user-attachments/assets/811f5d03-d6b2-4d47-8c8e-f1c1eb13e5d5" />

- Ethical Considerations Of Generative AI
  <img width="1118" height="735" alt="image" src="https://github.com/user-attachments/assets/0a32ed11-5429-414f-a785-41ccd343ce97" />

---

## 🙏 Acknowledgements

Special thanks to **IBM SkillsBuild**, **IBM watsonx.ai**, and **Kaggle** for providing tools and data to enable this project.

---

## 📬 Contact

If you have any questions or would like to collaborate:

**Atharva Vijay Suryawanshi**  
📧 atharvasuryawanshi7723@gmail.com  

---
