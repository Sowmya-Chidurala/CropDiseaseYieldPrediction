# 🌾 Two-Crop Disease Detection & Yield Prediction (Rice & Corn)

This project demonstrates an **end-to-end AI-based agricultural system** that combines **crop disease detection** using **Convolutional Neural Networks (CNNs)** with **weather-based yield prediction** using **Machine Learning**.
The system supports **two crops: Rice and Corn**, and is implemented as a **fully working Google Colab demo**.

---

## 🚀 Project Overview

Modern agriculture faces challenges such as crop diseases and unpredictable yields due to weather conditions.
This project addresses these challenges by:

* Detecting **crop health status** from leaf images
* Predicting **crop yield** based on weather parameters
* Integrating both tasks into a **single intelligent pipeline**

---

## 🧠 Features

* 🌱 **Multi-Crop Support**: Rice and Corn
* 🦠 **Disease Detection**: CNN-based image classification
* 🌦️ **Yield Prediction**: Weather-driven Random Forest regression
* 📊 **Visualization**: Leaf image results and yield bar charts
* ☁️ **Colab Compatible**: Runs end-to-end in Google Colab

---

## 🏗️ System Architecture

1. **Input**

   * Leaf image (Rice or Corn)
   * Weather data (Temperature, Rainfall, Humidity)

2. **Disease Detection**

   * CNN classifies leaf into:

     * Rice Healthy
     * Rice Diseased
     * Corn Healthy
     * Corn Diseased

3. **Crop Identification**

   * Crop type inferred from disease class

4. **Yield Prediction**

   * Separate Random Forest models for Rice and Corn
   * Predicts yield in tons/hectare

5. **Output**

   * Crop type
   * Disease status with confidence
   * Predicted yield
   * Visualization plots

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras** – CNN for disease detection
* **OpenCV** – Image processing
* **Scikit-learn** – Random Forest regression
* **NumPy & Pandas** – Data handling
* **Matplotlib** – Visualization

---

## 📁 Project Structure

```
├── disease_yield_demo.ipynb
├── rice_leaf.jpg
├── corn_leaf.jpg
├── README.md
```

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Install required libraries (already available in Colab)
3. Run all cells sequentially
4. The model will:

   * Train a demo CNN model
   * Train yield prediction models
   * Predict disease status and yield
   * Display visual outputs

---

## 🧪 Sample Output

```
Crop: Rice
Disease Status: Rice Healthy
Confidence: 72.45 %
Predicted Yield: 4.1 tons/hectare
```

Visual output includes:

* Leaf image with disease label
* Bar chart showing predicted yield

---

## 📌 Notes

* This project uses **dummy datasets** for demonstration purposes
* Designed for **academic learning, demos, and prototypes**
* Can be extended with:

  * Real-world datasets
  * More crops and diseases
  * IoT or mobile app integration

---

## 🔮 Future Enhancements

* Use real crop disease datasets (e.g., PlantVillage)
* Improve CNN accuracy with transfer learning
* Integrate real-time weather APIs
* Deploy as a web or mobile application
* Add satellite or drone imagery support

---

## 👩‍💻 Author

**Sowmya Chidurala**
AI & Machine Learning Enthusiast
Focused on smart agriculture and real-world ML applications

* Add **architecture diagrams**
* Rewrite it for **research / final-year project submission**
