# Handwritten-character-recognition
A deep learning-based project focused on recognizing handwritten characters. Includes datasets, training scripts, and an interactive demo to showcase the model's performance.
# Handwritten Character Recognition

![HCR Logo](https://via.placeholder.com/728x90.png?text=Handwritten+Character+Recognition+Project)

## 📜 **Overview**
Handwritten Character Recognition (HCR) leverages **Convolutional Neural Networks (CNN)** to identify handwritten characters from scanned images or inputs. This project was developed as part of a mini-project for **B.Tech in Artificial Intelligence and Machine Learning**, focusing on efficient and accurate recognition using modern machine learning techniques.

---

## 🎯 **Key Features**

- **Dataset:** Utilizes the EMNIST dataset with over 800,000 samples.
- **Algorithm:** Implemented using CNN with Keras and TensorFlow.
- **Accuracy:** Achieved 86.96% accuracy on test data.
- **Preprocessing:** Includes image normalization and noise reduction.
- **Save & Load Models:** Trained models can be exported and re-used.
- **Visualization:** Training performance graphs for accuracy and loss.

![Accuracy Graph](https://via.placeholder.com/300x200.png?text=Accuracy+Graph)
![Loss Graph](https://via.placeholder.com/300x200.png?text=Loss+Graph)

---

## 📂 **Folder Structure**

```
📦 Handwritten-Character-Recognition
├── dataset/               # Contains raw and preprocessed datasets
├── models/                # Saved model checkpoints
├── notebooks/             # Jupyter Notebooks for training and evaluation
├── results/               # Graphs, predictions, and accuracy reports
├── app/                   # Interactive web app for model testing
├── README.md              # Project documentation (this file)
└── LICENSE                # License information
```

---

## 📊 **Dataset Description**
The project uses the **EMNIST ByClass split**:

- **Training Samples:** 697,932
- **Testing Samples:** 116,323
- **Classes:** 62 (letters and digits)

### **Preprocessing Steps**
1. **Normalization:** Scales images to 28x28 grayscale and values between 0 and 1.
2. **Noise Removal:** Filters unwanted artifacts for better feature extraction.
3. **Segmentation:** Splits text into individual characters.

---

## 🛠️ **Technology Stack**

| Tool/Library         | Purpose                              |
|----------------------|--------------------------------------|
| **Keras**            | Building and training CNN models     |
| **TensorFlow**       | Backend for machine learning         |
| **NumPy**            | Numerical computations               |
| **OpenCV**           | Image preprocessing and transformations |
| **Matplotlib**       | Visualization of data and graphs     |

---

## 🚀 **Getting Started**

### Prerequisites
Ensure you have Python 3.8+ and the following libraries installed:

```bash
pip install tensorflow keras numpy matplotlib opencv-python
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Handwritten-Character-Recognition.git
   cd Handwritten-Character-Recognition
   ```
2. Open the `ModelTrain.ipynb` notebook to train the model.
3. Use `Segment.ipynb` to segment and predict handwritten text.

---

## 📈 **Results**
- **Accuracy Achieved:** 86.96%
- **Top Optimizer:** Adamax with the highest performance score of 89.53%

![Optimizer Comparison](https://via.placeholder.com/600x400.png?text=Optimizer+Comparison)

---

## 📜 **Future Scope**
- Expand recognition from single characters to entire sentences and paragraphs.
- Develop a front-end application using HTML and Bootstrap for better user interaction.

---

## 🤝 **Contributing**
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

---

## 📝 **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

![Footer](https://via.placeholder.com/728x90.png?text=Thank+You+For+Visiting!)
