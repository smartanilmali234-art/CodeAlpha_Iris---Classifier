# 🌸 Iris Flower Classification Web App

A complete **Machine Learning web application** built with Python and Streamlit that predicts the species of an iris flower based on user input features.

---

## 🚀 Live Demo

https://codealphairis---classifier-5cnybgzqthxc3cckrcd4wm.streamlit.app/

---

## 📌 Project Overview

This project uses the famous Iris dataset to classify iris flowers into three species:

* 🌼 Setosa
* 🌸 Versicolor
* 🌺 Virginica

The app allows users to:

* Input flower measurements
* Choose different ML models
* Visualize data
* See prediction results instantly

---

## ✨ Features

✔ 🎨 Beautiful UI using Streamlit
✔ 🧠 Multiple ML models:

* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

✔ 📊 Real-time data visualization
✔ 📈 Prediction probability charts
✔ 🎯 Confusion matrix & accuracy display
✔ 🌼 Image-based prediction output
✔ 🌍 Ready for cloud deployment

---

## 🛠️ Tech Stack

* **Python**
* **Scikit-learn**
* **Pandas / NumPy**
* **Matplotlib / Seaborn**
* **Streamlit**
* **Joblib**

---

## 📁 Project Structure

```bash
iris-classifier/
│── app.py
│── model.py
│── requirements.txt
│── runtime.txt
│── README.md
│
├── models/
│   ├── random_forest.pkl
│   ├── svm.pkl
│   ├── knn.pkl
│   ├── labels.pkl
│
├── assets/
│   ├── setosa.jpg
│   ├── versicolor.jpg
│   ├── virginica.jpg
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/iris-classifier.git
cd iris-classifier
```

---

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Train Models

```bash
python model.py
```

---

### 5️⃣ Run Application

```bash
streamlit run app.py
```

---

## 📊 Model Details

| Model         | Description                              |
| ------------- | ---------------------------------------- |
| Random Forest | Ensemble learning, high accuracy         |
| SVM           | Works well for classification boundaries |
| KNN           | Simple distance-based algorithm          |

---

## 📈 Output Example

* ✅ Predicted Flower Species
* 📊 Probability Distribution
* 📉 Confusion Matrix
* 📸 Flower Image

---

## 🌍 Deployment

You can deploy this app on:

* Streamlit Community Cloud
* Hugging Face Spaces
* Render

---

## 🧠 Future Improvements

* 🔐 User authentication system
* 📡 REST API using FastAPI
* 🐳 Docker containerization
* ☁️ Deployment on AWS / GCP
* 📊 Advanced analytics dashboard

---

## 👨‍💻 Author
   Name:Anil Mali
📧 Email:smartanilmali234@gmail.com
🔗 GitHub: https://github.com/smartanilmali234-art

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 🛠️ Contribute

---

## 📜 License

This project is open-source and available under the MIT License.
