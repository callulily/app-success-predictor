# app-success-predictor
Predicting app success on Google Play Store using user reviews and market data with machine learning.

This project analyzes data from Google Play Store apps and their user reviews to:
- Explore market trends through EDA
- Analyze sentiment patterns
- Build models to predict app success

---

## Files and Structure

| File | Description |
|------|-------------|
| `App_Success_Predictor.ipynb` | Main Jupyter Notebook with EDA, modeling, and evaluation |
| `app_success_predictor.pkl` | Trained ML model saved as a pickle file |
| `apps.csv` | Dataset containing metadata about Android apps |
| `user_reviews.csv` | Dataset with user reviews and sentiments |
| `README.md` | Project description and instructions |
| `LICENSE` | Open source license |
| `.gitignore` | Files ignored by Git |

---

## Datasets

- **apps.csv:**  
  Contains app name, category, rating, installs, price, size, etc.

- **user_reviews.csv:**  
  Includes app name, user sentiment (Positive/Neutral/Negative), and review text.

---

## ML Models Used

- Logistic Regression
- Random Forest
- Gradient Boosting

---

## Technologies

- Python
- pandas, NumPy
- scikit-learn
- seaborn, matplotlib
- Jupyter Notebook

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/callulily/app-success-predictor
   cd app-success-predictor

## Contact

Made with 💙 by **Aliya**
If you have any questions, feel free to reach out via [GitHub](https://github.com/callulily)
Or via email: karimovna04@mail.ru.
