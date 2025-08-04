# 🎬 Task 1 - Movie Genre Classification (CodSoft Internship)

This project is a machine learning model that classifies the genre of a movie based on its plot summary using natural language processing (NLP) techniques.

---

## 📂 Folder Structure
Task1_MovieGenre/
- train_data.txt # Training data (labeled with genres)
- test_data.txt # Test data (unlabeled)
- test_data_solution.txt # Actual genres for test data (for evaluation)
- movie_genre_classification.ipynb # Main notebook with full code
- README.md # This file


---

## 🧠 Technologies & Libraries Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- TfidfVectorizer
- Multinomial Naive Bayes

---

## 📌 Features

- Extracts genre and plot summary from structured `.txt` files
- Converts text data into numerical vectors using TF-IDF
- Trains a Naive Bayes classifier
- Evaluates performance on a separate test dataset
- Displays confusion matrix and classification metrics
- Allows genre prediction for custom movie plots

---

## ▶️ How to Run the Project

1. Open the folder in **VS Code** or **Jupyter Notebook**
2. Ensure the following files are present in the same folder:
   - `train_data.txt`
   - `test_data.txt`
   - `test_data_solution.txt`
   - `movie_genre_classification.ipynb`
3. Install dependencies (if not already):
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
4. Open and run the Jupyter notebook step-by-step:
```bash
    movie_genre_classification.ipynb
```
---

## 📈 Output Example
Accuracy on validation and test set

Classification report with precision/recall/F1

Confusion matrix (visual)

Sample genre predictions

---

## 📤 Exporting Predictions (Optional)

After predicting genres for the test data, the notebook also writes the predictions to a text file:

📄 `predicted_genres.txt`

Each line follows the format:

<ID> ::: <predicted_genre>

This matches the original input format, useful for submitting or verifying predictions.
