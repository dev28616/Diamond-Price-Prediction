# 💎 Diamond Price Prediction

Predicting diamond prices using machine learning techniques based on the "4 Cs" (Carat, Cut, Color, Clarity) and other relevant features.

![Diamond](https://user-images.githubusercontent.com/your-image-path/diamond.jpg) <!-- Replace with an actual image URL if available -->

---

## 📌 Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Dataset](#dataset)
* [Project Structure](#project-structure)
* [Installation](#installation)
* [Usage](#usage)
* [Model Performance](#model-performance)
* [Contributing](#contributing)
* [License](#license)

---

## 📖 Overview

This project aims to predict the price of diamonds by analyzing various attributes such as carat weight, cut, color, clarity, depth, table, and dimensions (x, y, z). Utilizing machine learning algorithms, the model provides accurate price estimations, assisting jewelers, gemologists, and consumers in making informed decisions.

---

## 🚀 Features

* **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
* **Exploratory Data Analysis (EDA)**: Visualizing data distributions and relationships between features.
* **Model Training**: Implementing regression algorithms like Linear Regression, Random Forest, and XGBoost.
* **Model Evaluation**: Assessing model performance using metrics such as RMSE, MAE, and R² score.
* **Web Application**: A user-friendly interface built with Flask to input diamond features and get price predictions.

---

## 📊 Dataset

The dataset used is sourced from [Kaggle's Diamond Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds). It contains over 50,000 records with the following features:

* **carat**: Weight of the diamond (0.2–5.01)
* **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
* **color**: Diamond color, from J (worst) to D (best)
* **clarity**: A measurement of how clear the diamond is (I1 (worst) to IF (best))
* **depth**: Total depth percentage = z / mean(x, y) = 2 \* z / (x + y)
* **table**: Width of the top of the diamond relative to the widest point
* **x**: Length in mm
* **y**: Width in mm
* **z**: Depth in mm
* **price**: Price in US dollars (\$326–\$18,823)

---

## 🗂️ Project Structure

```
├── artifacts/
├── notebooks/
│   └── data_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── prediction.py
├── templates/
│   └── index.html
├── application.py
├── requirements.txt
├── setup.py
└── README.md
```

* **artifacts/**: Contains serialized models and other artifacts.
* **notebooks/**: Jupyter notebooks for data analysis and experimentation.
* **src/**: Source code for data processing, model training, and prediction.
* **templates/**: HTML templates for the Flask web application.
* **application.py**: Main Flask application script.
* **requirements.txt**: Python dependencies.
* **setup.py**: Setup script for packaging.

---

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dev28616/Diamond-Price-Prediction.git
   cd Diamond-Price-Prediction
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

1. **Run the Flask application:**

   ```bash
   python application.py
   ```

2. **Access the web app:**

   Open your browser and navigate to `http://localhost:5000`.

3. **Predict diamond prices:**

   Input the diamond's features into the form and click "Predict" to see the estimated price.

---

## 📈 Model Performance

The model's performance was evaluated using the following metrics:

* **Root Mean Squared Error (RMSE)**: 1057.32
* **Mean Absolute Error (MAE)**: 842.15
* **R² Score**: 0.982

These results indicate a high level of accuracy in predicting diamond prices.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository.**

2. **Create a new branch:**

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit your changes:**

   ```bash
   git commit -m "Add your message"
   ```

4. **Push to the branch:**

   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a pull request.**

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*For any queries or suggestions, feel free to open an issue or contact the repository maintainer.*

---
