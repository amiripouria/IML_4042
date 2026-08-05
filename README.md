<div align="center">
  <h1> Intermediate Machine Learning </h1>
  <h3> K. N. Toosi University of Technology (KNTU) </h3>
  <h4> ARAS Neura Academy </h4>
  <p>
    <strong>Instructors:</strong> <a href="https://www.linkedin.com/in/mjahmadi/">Mohammad Javad Ahmadi</a>
</div>

## 📝 Project Title
> **Multiclass Classification of Brain Tumor MRI Images Using Transfer Learning and Model Explainability Analysis with Grad-CAM**

This project implements an intelligent deep learning-based classification system to categorize brain MRI images into four distinct classes: Glioma, Meningioma, Pituitary tumor, and No tumor. Serving as an automated medical triage tool, it utilizes Transfer Learning via a pre-trained EfficientNet-B0 architecture to balance parameter efficiency with high accuracy. To ensure the system is medically defensible and transparent, Grad-CAM is integrated to visualize the exact spatial regions influencing the model's predictions Furthermore, the model rigorously addresses the inherent class imbalance of medical datasets using structural mathematical interventions, including Class Weights and Focal Loss. Finally, the entire pipeline is deployed as a usable clinical prototype via an interactive Gradio web interface.

---

## 🎥 Product Pitch & Demos

📄 **[Project Report & Documentation (Google Drive)](Link-Here)**

---

## 👥 Team Members
| Name | Student ID | GitHub Profile | Role / Contribution |
| :--- | :--- | :--- | :--- |
| [Pouria Amiri] | `40115973` | [@amiripouria](https://github.com/amiripouria) | Deep Learning Architecture, Transfer Learning, & Gradio Dashboard Development, Data Preprocessing, Focal Loss Integration, & Evaluation Metrics (ROC-AUC, Grad-CAM) |

---

## 📂 Repository Structure
```text
Brain-Tumor-MRI-Classification/
├── src/               # Source code for algorithms, training pipelines, and main scripts
├── docs/              # Academic reports, ROC-AUC plots, and confusion matrices
├── assets/            # Sample Grad-CAM heatmaps, GUI screenshots, and media used in this README
└── README.md          # This file


---

## 📜 License
This project is licensed under the [MIT License](LICENSE).
