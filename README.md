# Health Insurance Cost Prediction

This project uses machine learning to predict health insurance premium charges based on user input such as age, sex, BMI, number of children, smoking status, and region. The application features a simple web interface built using Flask, allowing users to enter their details and receive real-time predictions.

## 🚀 Features

- Predicts insurance charges using a trained regression model
- Web-based interface for ease of use
- Preprocessing pipeline for feature transformation
- Built using Python, Flask, scikit-learn, and joblib

## 📊 Input Features

The model takes the following inputs:
- **Age**: Age of the individual
- **Sex**: Male or Female
- **BMI**: Body Mass Index
- **Children**: Number of children
- **Smoker**: Yes or No
- **Region**: Region in the US (northeast, northwest, southeast, southwest)

## 🛠️ Tech Stack

- Python
- Flask (for web app)
- scikit-learn (for ML model)
- joblib (for model serialization)
- HTML (for frontend)

## 📁 Project Structure

```
├── Healthprediction.py                  # Flask app script
├── Healthinsurance_prediction.ipynb     # Model training and evaluation
├── model.save                           # Trained model (serialized)
├── transf                               # Preprocessing transformer (serialized)
├── templates/
│   └── Frontend1.html                   # Web interface
├── static/                              # (Optional) for styling assets
└── README.md
```

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/health-insurance-prediction.git
   cd health-insurance-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:
   ```bash
   python Healthprediction.py
   ```

4. Open a browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

## 💡 Future Improvements

- Add data validation and error handling on the frontend
- Deploy the app using a cloud service (e.g., Heroku, AWS)
- Improve model accuracy with advanced algorithms or feature engineering

## 📄 License

This project is licensed under the [MIT License](LICENSE).

