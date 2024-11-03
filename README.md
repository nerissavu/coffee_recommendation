# ☕ Coffee Type Prediction App

A [Streamlit](https://streamlit.io) web application that recommends personalized coffee types based on user preferences using machine learning.

## 🎯 Features

* User-friendly interface with sidebar inputs
* Real-time predictions
* Support for multiple preference parameters:
  * Time of day
  * Coffee strength
  * Sweetness level
  * Milk type
  * Temperature
  * Flavoring options
  * Caffeine tolerance
  * Bean type
  * Size preferences
  * Dietary restrictions

## 🛠️ Installation

Access the website here https://coffeerecommendation-zuzqwwnmksuylgjysbuduf.streamlit.app/

## 📦 Required Dependencies

* `streamlit`
* `pandas`
* `scikit-learn`
* `pickle`

## 🚀 Usage

1. Ensure all model files are present:
   * `best_model.pkl`
   * `label_encoder.pkl`
   * `feature_names.pkl`

2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

3. Access the web interface through your browser (typically http://localhost:8501)

## 💻 How to Use

1. Select your preferences from the sidebar options:
   * Choose your preferred time of day
   * Select coffee strength
   * Specify sweetness level
   * Choose milk type
   * Select temperature preference
   * Indicate if you want flavored coffee
   * Set your caffeine tolerance
   * Choose coffee bean type
   * Select your preferred size
   * Specify any dietary restrictions

2. The app will automatically generate a coffee type recommendation based on your selections

## 🗃️ Model Files

The application requires three pickle files:

* `best_model.pkl` - Trained machine learning model
* `label_encoder.pkl` - Label encoder for coffee types
* `feature_names.pkl` - Feature names for input processing

