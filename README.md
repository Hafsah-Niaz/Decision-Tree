<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=FFB6C1&height=160&text=🌸%20Decision%20Tree%20🌸&fontColor=8B008B&fontSize=40&animation=twinkling" />
</p>

---

## 📌 Project Overview  

This project demonstrates **Decision Tree Regression** using **Python** and **Scikit-Learn** 🌷  
It predicts the **Chance of Admission** for students based on their **GRE Score**, showcasing how non-linear relationships can be captured with decision tree models.

---

## 🧠 Steps Performed  

### 1️⃣ Importing Required Libraries  
- **NumPy**, **Pandas** → for data handling  
- **Matplotlib** → for visualization  
- **Scikit-Learn** → for regression modeling  

---

### 2️⃣ Loading and Exploring the Dataset  
- Load data using `pandas.read_csv()`  
- Check shape using `.shape`  
- Preview data using `.head()`  

---

### 3️⃣ Data Preprocessing  
- Dropped unnecessary columns  
- Extracted **GRE Score (X)** and **Chance of Admit (Y)**  
- Reshaped data for model compatibility  

---

### 4️⃣ Data Visualization  
Visualized the relationship between **GRE Score** and **Chance of Admission** using scatter plots 🎨  


---

### 5️⃣ Splitting the Dataset  
- Used `train_test_split()`  
- 80% for training and 20% for testing  

---

### 6️⃣ Building and Training the Decision Tree Model  
- Created model using `DecisionTreeRegressor()`  
- Trained with `dt.fit(X_train, Y_train)`  

---

### 7️⃣ Making Predictions  
- Predicted test results using `dt.predict(X_test)`  
- Compared results with actual values  

---

### 8️⃣ Visualizing the Decision Tree  
Used `plot_tree()` from `sklearn.tree` to visualize the model structure 🌿  

---

## 📊 Results  

✨ The **Decision Tree Regression model** accurately predicts the **Chance of Admission** based on **GRE Score**.  
✨ The tree visualization provides interpretability of decision paths and thresholds.  

---

## 🧾 Dependencies  

Install the required libraries before running:  

```bash
pip install numpy pandas matplotlib scikit-learn
