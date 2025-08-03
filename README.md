# 🛡️ Network Intrusion Detection System (NIDS) using Machine Learning

This project focuses on building a robust Network Intrusion Detection System (NIDS) using supervised machine learning techniques to classify and detect different types of cyber-attacks. It uses IBM Watson Studio and AutoAI to automate model training, evaluation, and deployment.

---

## 📌 Problem Statement

With the rise in cyber threats, there is a growing need for automated systems that can analyze network traffic and distinguish between normal activity and malicious intrusions like DoS, Probe, R2L, and U2R. This project aims to develop a scalable and intelligent system to detect such attacks in real-time using machine learning.

---

## ⚙️ System Approach

- **Dataset:** Kaggle Network Intrusion Detection dataset  
- **Platform:** IBM Watson Studio with AutoAI  
- **Modeling:** Auto-generated pipelines with cross-validation  
- **Output:** Best model with 99.5% accuracy, ready for deployment

---

### 🖥️ System Requirements

- IBM Cloud Lite Account  
- IBM Watson Studio  
- Stable Internet Connection  
- Chrome/Firefox Browser

---

### 🧰 Libraries & Tools Used

- `Pandas`, `NumPy` – Data handling  
- `Scikit-learn` – ML algorithms  
- `AutoAI` – Automated modeling  
- `Matplotlib`, `Seaborn` – Visualization (optional)  
- IBM Cloud services for deployment

---

## 🤖 Algorithm & Deployment

- **Algorithm Used:** Snap Decision Tree Classifier (with Hyperparameter Optimization)  
- **Input Features:** protocol type, service, flag, src_bytes, dst_bytes, count, srv_count, etc.  
- **Training:** Automated using IBM AutoAI with data preprocessing, feature engineering, and model tuning  
- **Accuracy:** 99.5% (cross-validation)  
- **Deployment:** Model ready for deployment on IBM Cloud Lite using Watson Studio

---

## 🏁 Result

- 8 AutoAI pipelines were generated  
- **Pipeline 2** using **Snap Decision Tree Classifier (HPO)** was the top performer  
- Achieved **99.5% accuracy** on cross-validation  
- Successfully classified all attack types and ready for deployment

---

## ✅ Conclusion

This project demonstrated the effectiveness of using machine learning for network intrusion detection. The model achieved high accuracy and reliability using IBM Watson Studio's AutoAI. Challenges like class imbalance and high-dimensional data were handled efficiently. The system is suitable for deployment in real-time environments for proactive cybersecurity defense.

---

## 🔮 Future Scope

- Integrate real-time traffic for live threat detection  
- Use deep learning (LSTM/CNN) for more complex patterns  
- Improve detection of rare attacks like R2L and U2R  
- Add a dashboard for monitoring predictions  
- Extend the system to support multi-source logs and threat intelligence

---

## 📚 References

- [Kaggle Dataset – Network Intrusion Detection](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)  
- D. E. Denning, “An Intrusion-Detection Model,” *IEEE Transactions*, 1987  
- IBM Cloud Docs – [Getting Started with Watson Studio](https://cloud.ibm.com/docs/watson-studio)  
- Scikit-learn – [Decision Trees](https://scikit-learn.org/stable/modules/tree.html)

---

## 🚀 How to Use

1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/nids-ml-ibmcloud.git
