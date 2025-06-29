# Final-Exam-Model-Deployment-in-the-Cloud_Group-10

# Weather Detection System

A deep learning-based web application for classifying weather conditions from images. This project uses a TensorFlow-trained convolutional neural network model to predict one of four weather types: Cloudy, Rainy, Shiny, or Sunrise.

---

## 🚀 Project Overview

The Weather Detection System allows users to upload a weather photo, which the model then analyzes to predict the current weather condition. The web app is built with **Streamlit** for an interactive and user-friendly interface, making it easy for anyone to use.

---

## ⚙️ Features

- Supports image upload in JPG, JPEG, PNG, and HEIC formats.
- Converts HEIC images automatically to a compatible format.
- Image preprocessing to fit model input size (150x150 pixels).
- Normalizes image data before prediction.
- Displays predicted weather class with corresponding emoji:
  - 🌥️ Cloudy
  - 🌧️ Rainy
  - ☀️ Shiny
  - 🌅 Sunrise

---

## 📁 Repository Contents

- `Weather_Classification-Model.h5` — Pre-trained TensorFlow model.
- `app.py` — Streamlit application code for user interface and model inference.
- Dataset preparation and training scripts (for reference):
  - Data split into training and validation sets with an 80/20 ratio.
  - Organized multi-class weather image dataset with 4 categories: Cloudy, Rain, Shine, Sunrise.

---

## 🛠️ Technologies Used

- Python 3.x
- TensorFlow/Keras for model training and inference
- Streamlit for building the web app UI
- PIL (Pillow) for image processing
- NumPy for numerical operations

---

## 📦 Dataset Preparation (Brief)

- Source dataset contains four classes: Cloudy, Rain, Shine, Sunrise.
- Dataset is randomly shuffled and split into:
  - 80% training data
  - 20% validation data
- Images are copied to separate folders for training and validation to maintain the original dataset intact.

---

## 💻 How to Run Locally

1. Clone this repository.
2. Install required packages:
   ```bash
   pip install streamlit tensorflow pillow numpy


3. Place the pre-trained model file Weather_Classification-Model.h5 in the root directory.
4. Run the Streamlit app:
   streamlit run app.py
5. Open the provided local URL in your browser.
6. Upload an image and click the detect button to see the predicted weather.

## 📈 Model Details
The model is a convolutional neural network trained on the multi-class weather dataset to recognize and classify weather conditions from images. It performs image resizing, normalization, and prediction using TensorFlow.

## 🙌 Contribution
Feel free to fork this repository and improve the model, add more weather categories, or enhance the web app UI. Contributions and suggestions are welcome!

## 📫 Contact
For questions or feedback, please reach out via glennvargas01@gmail.com



