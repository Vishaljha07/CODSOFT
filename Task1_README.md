# 📧 Task 1 - Spam SMS Detection

## 📌 Internship Task

**Internship:** CodSoft Machine Learning Internship

**Task:** Spam SMS Detection

---

## 📖 Project Description

This project is a Machine Learning model that classifies SMS messages as Spam or Ham (Legitimate Messages).

The model uses TF-IDF Vectorization and Multinomial Naive Bayes to identify spam messages based on their text content.

---

## 📊 Dataset

Dataset: Spam SMS Dataset

Features:
- SMS Messages

Target:
- Spam
- Ham (Not Spam)

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Techniques

- TF-IDF Vectorization
- Multinomial Naive Bayes

---

## ⚙️ Steps Performed

1. Imported the dataset
2. Removed unnecessary columns
3. Renamed dataset columns
4. Converted labels into numerical values
5. Applied TF-IDF Vectorization
6. Split dataset into training and testing sets
7. Trained the model using Multinomial Naive Bayes
8. Evaluated model accuracy
9. Tested custom SMS messages

---

## ✅ Model Performance

Accuracy Achieved:

```text
96.23%
```

---

## 💬 Sample Predictions

### Example 1

Input:

```text
Congratulations! You have won a free iPhone. Click now.
```

Output:

```text
Spam Message
```

---

### Example 2

Input:

```text
Hello, how are you doing today?
```

Output:

```text
Ham Message
```

---

## ▶️ How to Run

1. Open `Spam_1st.ipynb`
2. Ensure `spam.csv` is present in the same folder
3. Run all cells sequentially
4. Check model accuracy and predictions

---

## 👤 Author

**Vishal Jha**

---

## 🌟 Acknowledgement

Thanks to **CodSoft** for providing this Machine Learning Internship opportunity.
