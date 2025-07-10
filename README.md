# JEE_COLLEGE_PREDICTOR-USING-MACHINE-LEARNING
🚀AI-powered tool to predict top 1 or top N engineering colleges based on JEE rank, category, and preferences using Machine Learning.

* 📧 Email changed to: `pakhareamol300@gmail.com`
* 🔗 LinkedIn profile added: `https://www.linkedin.com/in/amolpakhare/`

---
````markdown
# 🎓 JEE College Assistant Using Machine Learning

## ℹ️ Introduction

**JEE College Assistant** is an intelligent prediction system designed to help students make informed decisions about their **college and branch options** based on their **JEE rank and preferences**.

Every year, lakhs of students face difficulty in understanding which colleges and courses they might be eligible for. This tool uses real-world counseling data and Machine Learning to give personalized, data-driven recommendations.

---

## 🧠 Project Highlights

- ✅ Built on a dataset of **1,00,000+ rows** from official JoSAA and college counseling records.
- 🎯 Predicts **Top 1** or **Top N** colleges based on rank, category, preferences.
- 📊 Uses **K-Nearest Neighbors (KNN)** algorithm for multi-output prediction.
- 🧪 Achieves over **81% average accuracy** across institute, program, and degree predictions.
- 🖥️ Interactive frontend using Flask (React optional).
- 📂 Open-source and customizable for student, counselor, or institutional use.

---

## 🖼️ Screenshots

### 🎯 Result for Top 3 Colleges  
![Top 3 Prediction](https://github.com/user-attachments/assets/52eaae4e-470f-485b-bb65-dc7fee9c7673)

### 🎯 Result for Top 1 College  
![Top 1 Prediction](https://github.com/user-attachments/assets/fc275af8-4998-412f-bb03-3eee81da946c)

---

## 🌐 Technologies Used

| Layer       | Stack                                      |
|-------------|---------------------------------------------|
| **Frontend**  | HTML, CSS, JavaScript (React Optional)     |
| **Backend**   | Python, Flask or Django                    |
| **Database**  | CSV/JSON or SQL/NoSQL                      |
| **ML Model**  | K-Nearest Neighbors (KNN), Scikit-learn    |
| **Tools**     | Pandas, NumPy, Matplotlib, Jupyter Notebook|

---

## 🌟 Key Features

- 🎓 **College Predictor** – Recommends best-fit institutes based on JEE rank.
- 🛠️ **Branch Predictor** – Suggests possible branches in each eligible college.
- 📊 **Filters** – Sort or customize by category, marks, gender, and state quota.
- 💡 **Smart Customization** – Students can prioritize branches, locations, or institute types.
- 🔗 **External Links** – Optionally connects to college sites (Careers360, CollegeDunia, etc.).

---

## ⚙️ Implementation Details

- **Dataset**: Over **100,000 rows** containing institute name, program, degree, closing ranks, category, gender, home state.
- **Preprocessing**:
  - Cleaned missing values.
  - Normalized ranks.
  - Encoded categorical variables.
- **Model Used**: `KNeighborsClassifier`
  - Predicts: Institute Name, Program Name, Degree.
  - Distance-based recommendation with multi-label output.
- **Frontend**: Flask app that takes user input and displays the predicted top colleges.

---

## ✅ Model Accuracy

| Prediction Target     | Accuracy |
|------------------------|----------|
| Institute Name         | 75.3%    |
| Program Name           | 75.6%    |
| Degree Type            | 93.8%    |
| **Mean Accuracy**      | **81.6%**|

This performance demonstrates strong reliability in providing realistic admission possibilities.

---

## 🚀 How to Use

### Option 1: Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/JEE-College-Predictor.git
   cd JEE-College-Predictor
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:

   ```bash
   python app.py
   ```

### Option 2: Jupyter Notebook

* Open the `.ipynb` file.
* Run all cells to view predictions and charts.
* Modify inputs to simulate different scenarios.

---

## 🤝 Contributing

Contributions are welcome! Whether it's fixing bugs, improving UI, or adding features, feel free to open issues or submit a pull request.

---

## 📧 Contact

📩 Email: [pakhareamol300@gmail.com](mailto:pakhareamol300@gmail.com)
🔗 LinkedIn: [linkedin.com/in/amolpakhare](https://www.linkedin.com/in/amolpakhare/)
📬 Form: [Submit a Query](https://forms.gle/cEcJ9uEiz1XVbsuw8)

---

## 💬 Inspirational Quote

> **"In the realm of data, every pattern is a path, and every insight is a step toward smarter decisions."**

---

## 📌 Future Enhancements

* ✅ Add **state-wise cutoff filtering**
* 🔄 Integrate **Live JoSAA Counseling Updates**
* 📱 Build a mobile app version
* 🔍 Use **LLMs for Natural Language Inputs** like: “Suggest best CS colleges under 10k rank.”

---

⭐ Don't forget to **star** this repo if you find it helpful!

```

---
