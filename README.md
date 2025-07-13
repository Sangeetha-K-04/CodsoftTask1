 # 🌸 Iris Flower Classification - CodSoft Internship Task 2

> ✨ A bloom of Machine Learning meets the elegance of data science 🌼

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg" alt="Iris Flower" width="300">
</p>


---

## 📌 Project Snapshot

Welcome to one of the most classic — yet essential — machine learning challenges:  
**Classifying Iris flowers** based on their petal and sepal dimensions.

This project is built as part of my **CodSoft Data Science Internship** and focuses on:
- Understanding patterns in floral measurements 🌸
- Building a robust classification model 🌿
- Visualizing insights for humans to interpret 🌈

> Let’s predict the type of flower… one petal at a time! 🧠🌼

---

## 📂 Dataset Details

The dataset contains **150 samples** of Iris flowers, equally divided into 3 species:
- **Setosa**
- **Versicolor**
- **Virginica**

Each sample includes 4 key features:
- 🌿 Sepal Length
- 🌿 Sepal Width
- 🌸 Petal Length
- 🌸 Petal Width

> These are the floral fingerprints that help us identify the species.

---

## 🛠️ Tools & Tech Stack

| Tool | Purpose |
|------|---------|
| **Python**  | Programming backbone |
| **Pandas & NumPy** | Data handling and manipulation |
| **Seaborn & Matplotlib**  | Data visualization |
| **Scikit-learn**  | Machine learning and evaluation |

---

## 🔍 Exploratory Data Visuals

### 📊 Species Count
Displays how balanced the dataset is across the three flower types.

### 📦 Boxplot - Petal Length by Species
A crystal-clear view of how each flower species varies in petal length.

### 📈 Scatter Plot - Petal Length vs Width
Shows natural clustering — hinting how well these two features separate the species.

### 🧠 Feature Importance
Highlights which measurements matter most in the model’s decisions.

---

## 🤖 Model: Random Forest Classifier

Random Forest is a powerful, tree-based ensemble method. 🌲🌲🌲  
It learns from multiple decision trees and makes accurate predictions by taking the majority vote — great for classification problems like this!

---

## 🧪 Performance & Results

After training the model, we evaluate its performance using:
- ✅ **Accuracy Score**
- 📋 **Classification Report**
- 🔢 **Confusion Matrix**
- 🌟 **Feature Importance Bar Chart**

And guess what? The model nailed it! 🎯

### 📈 Sample Output

```bash
✅ Accuracy: 100.0 %

📋 Classification Report:
              precision    recall  f1-score   support

     setosa       1.00      1.00      1.00        10
 versicolor       1.00      1.00      1.00        10
  virginica       1.00      1.00      1.00        10
```



![Species Count](https://github.com/Sangeetha-K-04/CodsoftTask1/blob/main/iris1.png?raw=true)



![Petal length distribution](https://github.com/Sangeetha-K-04/CodsoftTask1/blob/main/iris2.png?raw=true)



![Petal length vs Width by species](https://github.com/Sangeetha-K-04/CodsoftTask1/blob/main/iris3.png?raw=true)



![Petal length vs Width by species](https://github.com/Sangeetha-K-04/CodsoftTask1/blob/main/iris4.png?raw=true)



![Petal length vs Width by species](https://github.com/Sangeetha-K-04/CodsoftTask1/blob/main/iris5.png?raw=true)



---

 ## 💻 How to Run the Project

### 1️⃣ Clone this Repository

```bash
git clone https://github.com/Sangeetha-K-04/CodsoftTask1.git
cd CodsoftTask1

```

### 2️⃣ Install Required Libraries

```bash
pip install pandas seaborn matplotlib scikit-learn
```

### 3️⃣ Run the Project

```bash
python iris_classification.py
```
