# 📌 Categorical Encoding Techniques in Machine Learning

This repository demonstrates different techniques used to encode categorical variables for Machine Learning models.
Categorical features cannot be directly used in ML models. Therefore, they need to be converted into numerical format. This project explores and implements the most commonly used encoding methods.

---

## 🔍 Techniques Covered

### 1️⃣ Label Encoding

- Converts each category into a unique integer value.
- Commonly used to encode the **target/output variable (y)** in classification problems.
- Suitable when the target variable is categorical (e.g., Yes/No, True/False, Spam/Not Spam).
- Not recommended for nominal input features because it may introduce unintended numerical order.

---

### 2️⃣ Ordinal Encoding

- Used when categories have meaningful order.
- Example: `Low < Medium < High`
- Maintains ranking information between categories.

---

### 3️⃣ One Hot Encoding

- Creates separate binary columns for each category.
- Best suited for **nominal categorical variables**.
- May increase dimensionality when categories are large.

---

### 4️⃣ One Hot Encoding using Most Frequent Categories

- Only the most frequent categories are encoded.
- Rare categories are grouped together.
- Helps reduce dimensionality in high-cardinality features.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 🎯 Objective

The goal of this project is to understand:

- Why encoding is required
- Differences between encoding techniques
- When to use which method
- Impact on model performance and dimensionality

---

## 🚀 Learning Outcomes

After completing this project, you will understand:

- Difference between nominal and ordinal categorical variables
- Advantages & disadvantages of each encoding technique
- Practical implementation using Scikit-learn
- How encoding affects feature space and dimensionality

---

## 📊 Future Improvements

- Compare model accuracy after applying different encoding techniques
- Integrate encoding inside an ML Pipeline
- Add performance comparison table


## 📌 Author

**Ishaan Sharma**  
B.Tech Artificial Intelligence & Machine Learning (3rd Year)


## 📂 Project Structure
