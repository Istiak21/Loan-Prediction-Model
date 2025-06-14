# 🏦 Loan Eligibility Checker Web App

This is a simple web application built using **Streamlit** that predicts whether a loan application is **Approved** or **Rejected** based on the applicant’s gender, marital status, monthly income, and loan amount. The prediction is powered by a pre-trained machine learning model stored in `classifier.pkl`.

---

## 🚀 Features

- Clean and user-friendly web interface.
- Takes user inputs through dropdowns and numeric fields.
- Uses a machine learning model to predict loan eligibility.
- Displays result instantly on the screen.

---

## 🧠 How It Works

1. User selects:
   - Gender (Male / Female / Other)
   - Marital Status (Unmarried / Married / Other)
2. User enters:
   - Monthly Income (in ₹)
   - Loan Amount (in ₹)
3. The app converts categorical values to numerical.
4. These values are passed into the loaded machine learning model.
5. The model returns a binary output — `0` for Rejected, `1` for Approved.
6. The app displays the result on the screen.

---
