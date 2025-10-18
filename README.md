# 🌟 ML-Powered Fitness & Activity Tracker

This project is a **MATLAB-based Fitness & Activity Tracker** that leverages **sensor data** and **machine learning** to monitor physical activity, calculate key fitness metrics, classify activities, and provide visualizations of movement. It was developed as part of a health and wellness hackathon project.

---

## ✨ Key Features

### 1. Multi-Sensor Data Capture
- Processes **GPS** and **accelerometer** data.
- Converts latitude, longitude, and altitude to local **x, y, z coordinates** for trajectory mapping.
- Handles timestamps and synchronizes multiple sensor streams.

### 2. Metric Calculations
- **Total Distance Traveled**: Uses latitude and longitude data to compute accurate distances in meters.
- **Step Count**: Estimates steps based on stride length.
- **Velocity & Speed**: Computes raw and filtered velocities using **Exponential Moving Average (EMA)** filtering.
- **Calorie Estimation**: Calculates calories burned for sitting, walking, and running using MET values and user weight.

### 3. Activity Classification
- **Velocity-Based Classification**: Differentiates between sitting, walking, running, and fast running using smoothed velocity thresholds.
- **Machine Learning Classification**: Uses a trained neural network model to classify activities based on accelerometer data.
- **Pie Chart & Histogram Visualizations**: Displays activity distribution and acceleration patterns.

### 4. Path Visualization
- Plots **3D trajectory** from GPS data with start and end markers.
- Visualizes velocity components and smoothed velocity over time.
- Color-coded segments based on movement classification.

### 5. Anomaly Detection
- Detects **NaN values** and interpolates missing data.
- Flags sudden velocity jumps or GPS anomalies and applies median filtering for correction.

---

## 🛠 Technology Stack
- **Language**: MATLAB
- **Toolboxes**: Statistics and Machine Learning Toolbox
- **Core Functions Used**:
  - `latlon2local` for converting GPS to local coordinates.
  - `timetable2table` for handling time-series data.
  - Filtering functions (`filter`, `movmean`) for velocity and acceleration smoothing.
  - ML model prediction using `trainedModelNN.predictFcn` or `trainedModel5.predictFcn`.

---

## 🚀 Getting Started

### Prerequisites
- MATLAB (R2024a or later recommended)
- Statistics and Machine Learning Toolbox

### Installation and Setup
1. Clone the repository:
```bash
git clone London-MATLABATHON
cd London-MATLABATHON
```

2. **Open MATLAB and navigate to the project directory**.

3. **Ensure you have the example input files**:

```text
ExampleData.mat        % Contains Position and Acceleration timetables
trainedModelNN.mat     % For activity classification (or)
trainedModel5.mat
```
4. Run 
