# 🎯 Face Detection Form App

A simple Flask web app that collects user details via a form and captures their face using the webcam. The data is saved locally and logged into an Excel file.

## 🚀 Features
- 📸 Face capture using webcam (OpenCV)
- 📝 User form input (Name, Email, etc.)
- 💾 Saves face image & form data
- 📊 Stores responses in data.xlsx

## 🛠 Setup

bash
pip install flask opencv-python openpyxl


## ▶ Run the App

bash
python app.py


Then open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

## 📁 Output

- Face images saved in static/faces/
- Form data saved in data.xlsx

---

✅ Make sure your webcam is connected and accessible.
