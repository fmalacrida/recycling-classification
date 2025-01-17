# 🗑️ Recyclable and Household Waste Classification Project

## 📂 Project Overview
This project focuses on developing a machine learning model for classifying various types of recyclable and household waste. Using a fine-tuned **MobileNetV2** model, the goal is to automate waste classification and support efficient waste management practices.

## 🏗️ Project Structure
```
├── dataset/
│   ├── images/
│   │   ├── Plastic/
│   │   │   ├── default/
│   │   │   └── real_world/
│   │   ├── Paper and Cardboard/
│   │   └── Metal/
│   └── test/   # Contains unsorted images for testing
├── models/
│   └── saved_model.h5
├── notebooks/
│   └── recycling_final.ipynb
├── results/
│   └── confusion_matrix.png
└── README.md
```

## 📊 Dataset Description
- **Source:** Custom Google Images and the provided waste classification dataset.
- **Structure:**
  - **default/**: Studio-like images for training.
  - **real_world/**: Real-world images for validation.
  - **test/**: Unsorted images for model testing.

## 🛠️ Technologies Used
- **Python** 3.x
- **TensorFlow/Keras**
- **Pandas & NumPy**
- **Matplotlib & Seaborn** (for visualization)
- **Sklearn** (for evaluation metrics)

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/fmalacrida/recycling-classification.git
   cd recycling-classification
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   - Open `notebooks/recycling_final.ipynb` in Jupyter Notebook or VS Code.
   - Execute the cells to load data, train the model, and evaluate performance.

4. **Test the Model:**
   - Place images in the `test/` folder.
   - The notebook includes code to predict and evaluate test images.

## 📈 Results
- **Model Used:** Fine-Tuned **MobileNetV2**
- **Overall Accuracy:** ~74%
- **Best-Performing Classes:** Organic waste, paper products.
- **Classes Needing Improvement:** Metal cans, plastic lids.

## 🔎 Evaluation Metrics
- **Accuracy**
- **Precision, Recall, F1-Score**
- **Confusion Matrix**

## 📦 Future Improvements
- Implement more data augmentation for underrepresented classes.
- Explore more advanced models (e.g., ResNet50).
- Balance the dataset to handle class imbalance.

## 🤝 Contributing
Feel free to submit issues or pull requests to improve the project.

---

**Author:** Felipe M

---

*Let's build a cleaner and greener future!* 🌿

