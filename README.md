# Urban Flood Prediction - Del Carmen, Iligan City

An IoT-based system utilizing **Hydrologic Analysis** and **LSTM Neural Networks** to provide a 5-minute lead time for urban flood alerts.

##  Key Features
- **Hydrologic Preprocessing:** Dual-window median smoothing for noise reduction.
- **Feature Engineering:** Inclusion of spatial gradients, first-order trends, and lag features (t-5, t-10, t-15).
- **ML Architecture:** Stacked LSTM (64/32 units) with Dropout (0.2).

##  Performance
- **MAE:** 3.15
- **RMSE:** 6.53

##  Tech Stack
- **Hardware:** ESP32 T-A7670E, Ultrasonic Sensors.
- **Backend:** Node.js, Firebase Realtime Database.
- **Data Science:** Python (Pandas, TensorFlow, Scikit-Learn).

##  Model Download
The pre-trained LSTM model can be downloaded from the [latest release](https://github.com/YOUR_USERNAME/YOUR_REPO/releases/latest).
