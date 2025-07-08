# 🔬 Diabetic Retinopathy Detection using Custom Neural Network Architectures

This repository documents a school project in which we explored the detection of **diabetic retinopathy** from retinal images using **deep learning**, with a particular focus on designing our **own neural network architecture** instead of relying on pre-trained models like ResNet.

---

## 🎯 Project Objective

The goal of this project was to:
- Understand how diabetic retinopathy can be detected through medical imagery.
- Design and experiment with **custom convolutional neural networks** (CNNs) from scratch.

---

## 🧠 Why Custom Architectures?

Instead of using popular and well-performing architectures like **ResNet**, **Inception**, or **EfficientNet**, we challenged ourselves to:
- Develop our own architecture from first principles.
- Explore the trade-offs between **model complexity**, **training performance**, and **generalization**.
- Gain a deeper understanding of CNN design through experimentation and research.

We **intentionally avoided using previous Kaggle solutions or community notebooks**. The goal was not to optimize accuracy at all costs, but to treat this project as a learning experience in architectural design and deep learning fundamentals.

We also acknowledged from the start that our custom model would likely **underperform** compared to battle-tested architectures—but this was an intentional decision for learning purposes.

---

## 📚 Dataset

We used the publicly available dataset from the **[Kaggle Diabetic Retinopathy Detection challenge](https://www.kaggle.com/competitions/diabetic-retinopathy-detection/overview)**.

To streamline training and experimentation:
- One of our team members **downloaded the full dataset**.
- **Data augmentation** techniques were applied (e.g., rotation, flipping, brightness/contrast adjustments) to enrich the dataset and reduce overfitting.
- After augmentation, we created and shared **multiple versions of the dataset in different sizes** to accommodate varying compute limitations and training goals.

This approach allowed everyone in the class to select a dataset version that best matched their needs. It was a key step in making the project more accessible and efficient under school constraints.

---

## 💻 Implementation

All experimentation, training, evaluation, and analysis were conducted in a **Kaggle Notebook** environment.

🔗 You can access our full notebook here:  
👉 **[Kaggle Notebook Link](https://www.kaggle.com/code/hugolemonnier/project-nn-melih-sahman-et-hugo-lemonnier)**

---

## 📊 Results & Observations

- While our custom network did not outperform popular architectures, we were able to reach promising levels of accuracy with a lightweight model.
- The exercise provided valuable insight into how architectural design decisions affect model performance and training behavior.

---

## 🧾 Conclusions

- Designing CNNs from scratch helped solidify our understanding of convolutional layers, overfitting, and model optimization.
- We chose **not to replicate or adapt prior Kaggle solutions**, ensuring the architecture and results were the product of our own research and experimentation.

---

## 👥 Team

This project was completed as part of a school assignment by a group of students.

**Special thanks to:**  
**Melih Sahman** – for collaboration and contributions throughout the project.  

---

## 📎 License

This repository is licensed under the [MIT License](./LICENSE).  
It is intended for educational and non-commercial use only.
