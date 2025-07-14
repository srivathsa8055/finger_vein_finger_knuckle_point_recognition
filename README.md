
# 🔍 Finger Vein & Knuckle Biometric Authentication Project
## 📌 Overview

This project focuses on biometric authentication using **finger vein** and **knuckle print** patterns. Both these modalities provide unique and secure identifiers for use in:
- Banking and secure financial transactions
- Forensic and criminal identification
- High-security access control systems

The repository includes:
- Data preprocessing
- Image visualization
- Feature extraction
- Optional: Machine Learning-based classification

---

## 📂 Project Structure

```
finger_vein_knuckle_project/
│
├── finger_vein_kuckle_project_n.ipynb   # Jupyter Notebook with the full workflow
├── data/                                # Folder for raw finger vein and knuckle images
├── results/                             # Output images and analysis results
├── images/                              # Example and sample images used in documentation
└── README.md                            # Project documentation
```

---

## 🛠️ Technologies & Libraries

| Library/Tool       | Purpose                      |
|--------------------|------------------------------|
| Python 3.x         | Programming Language         |
| Jupyter Notebook   | Interactive Environment      |
| OpenCV             | Image Processing             |
| NumPy & Pandas     | Data Manipulation            |
| Matplotlib         | Visualization                |
| Scikit-Learn       | Machine Learning (optional)  |

---

## 🚀 Getting Started

### ✅ Prerequisites

Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib opencv-python scikit-learn
```

### ✅ Steps to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run the notebook:
```
finger_vein_kuckle_project_n.ipynb
```

---

## 🔬 Methodology

### 🔎 Image Preprocessing

- Noise reduction
- Contrast enhancement
- ROI (Region of Interest) extraction

Example preprocessed images:
<img width="1065" height="576" alt="fingervein" src="https://github.com/user-attachments/assets/1186877b-f711-4d5d-b16f-cdaed663dd61" />

<img width="1072" height="607" alt="finger_knuckle" src="https://github.com/user-attachments/assets/73cc9134-a9bb-478c-bb27-75ec9e8566b8" />


### 📈 Feature Extraction

- Texture features
- Edge detection (e.g., Canny, Sobel)
- Statistical analysis (mean, variance)

### 🧠 Classification (Optional)

- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Potential Deep Learning with CNNs for future work

---

## 📊 Sample Results

<img width="606" height="472" alt="accuracy_graphResNet50" src="https://github.com/user-attachments/assets/8e1588c1-7906-46d3-a19b-b07f3da00042" />

<img width="728" height="510" alt="accuracy_graphvgg16" src="https://github.com/user-attachments/assets/99575d51-bcd4-4c8c-90db-320f19aff6fd" />

<img width="872" height="277" alt="Model_performance_comparision" src="https://github.com/user-attachments/assets/8a6c1918-9ea1-4104-8ec3-149f8ef63d05" />

Output include:
- Model classification metrics like Accuracy and Precision
-Model Acurracy Graph
---

## 🚧 Future Enhancements

- ✅ Deep learning model integration
- ✅ GUI development for user-friendly access
- ✅ Performance optimization on larger datasets

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork this repository
2. Create a new branch:
```bash
git checkout -b feature/YourFeature
```
3. Commit your changes:
```bash
git commit -m "Add Your Message"
```
4. Push to your branch:
```bash
git push origin feature/YourFeature
```
5. Open a pull request.

---

## 🙌 Acknowledgements

- Biometric Research Community
- OpenCV and Scikit-Learn Developers
- Open Datasets on Finger Vein and Knuckle Biometrics

---

> Developed by **Srivathsa Acharya** 
