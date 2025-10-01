# Asthma-Prediction-AIML-
Asthma Prediction using machine learning (Random Forest)

# 🫁 Asthma Prediction Using Machine Learning

This project aims to predict the likelihood of asthma in patients based on various health parameters using **Machine Learning**.  
It includes a **Tkinter-based GUI application** that allows users to input their parameters and receive predictions.

---

## 📋 Project Overview
Asthma is a chronic respiratory disease that can be mitigated with early diagnosis and treatment.  
This project uses a dataset containing patient parameters (age, family history, smoking habits, etc.) to train a **Random Forest Classifier**.  
The trained model predicts whether a person is likely to develop asthma.

---

## ✨ Features
- 📊 **Machine Learning Model:** Trained on a CSV dataset of asthma patient parameters.
- 🖥️ **Interactive GUI:** Developed with Tkinter to easily input patient data.
- 📈 **Prediction Result:** Displays the likelihood of asthma instantly.
- 🔥 **End-to-End Workflow:** Data loading → preprocessing → training → prediction → GUI deployment.

---

## 🗂️ Project Structure
Asthma-Prediction-ML/
├── asthma_model.pkl # Trained machine learning model
├── synthetic_asthma_dataset.csv # Dataset used for training
├── gui_app.py # Tkinter GUI application
├── train_model.py # Script to train the model
├── README.md # Project documentation
└── requirements.txt # Python dependencies

yaml
Copy code

---

## 🛠️ Requirements
- Python 3.8 or above
- Required Python libraries:
  ```bash
  pip install pandas scikit-learn tkinter
(Tkinter usually comes pre-installed with Python.)

🚀 How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/<your-username>/Asthma-Prediction-ML.git
cd Asthma-Prediction-ML
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the GUI application:

bash
Copy code
python gui_app.py
Enter patient parameters in the GUI to get the asthma prediction.

📂 Dataset
The project uses a synthetic asthma dataset that contains patient health parameters such as:

Age

Gender

Smoking Habits

Family History

BMI

Air Pollution Exposure

Wheezing, Shortness of Breath, etc.

⚠️ For demonstration and educational purposes only. Replace with a real clinical dataset for production use.

🧠 Machine Learning Workflow
Data preprocessing (handling missing values, encoding categorical data)

Feature selection and scaling

Model training using Random Forest Classifier

Model evaluation using metrics like accuracy, precision, and recall

Deployment with a user-friendly GUI

📸 Screenshots
(Add screenshots of your GUI application here)
Example:

📜 License
This project is licensed under the MIT License - you are free to use and modify it.

🤝 Contributing
Contributions are welcome!
If you’d like to improve the project, feel free to:

Submit an issue

Fork the repo and create a pull request

Suggest new features or optimizations

📚 References
scikit-learn Documentation

Tkinter Documentation

World Health Organization (WHO): Asthma Facts

⚠️ Disclaimer
This project is for educational and research purposes only and should not be used as a substitute for professional medical advice or diagnosis.