# Spam-Detector

A Machine Learning-based Spam Detection application built with **Python**, **Scikit-learn**, and **Streamlit**. The application classifies SMS or text messages as **Spam** or **Not Spam** using a trained machine learning model.

## 🚀 Features

* Detects spam messages instantly
* Clean and interactive Streamlit interface
* Pre-trained Machine Learning model
* Text preprocessing and vectorization
* Fast and accurate predictions

## 🛠️ Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Joblib

## 📂 Project Structure

```
Spam Detector/
│── dataset/
│── src/
│── model.pkl
│── vectorizer.pkl
│── requirements.txt
│── README.md
```

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/spam-detector.git
```

2. Navigate to the project directory:

```bash
cd spam-detector
```

3. Create a virtual environment:

```bash
python -m venv venv
```

4. Activate the virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

5. Install dependencies:

```bash
pip install -r requirements.txt
```

6. Run the application:

```bash
cd src
streamlit run app.py
```

> If your main Streamlit file has a different name, replace `app.py` with the correct filename.

## 📊 Model

The model is trained using Scikit-learn and saved as:

* `model.pkl`
* `vectorizer.pkl`

These files are used for making predictions without retraining the model.

## 📸 Output

Users can enter any SMS or text message, and the application predicts whether it is:

* ✅ Not Spam
* 🚫 Spam

