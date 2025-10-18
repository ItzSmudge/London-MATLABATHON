# 🌟 Health & Wellness Tracking Suite

This project is a two-part suite developed during the **[Insert Hackathon Name Here]** hackathon, focusing on leveraging **data science** and **algorithmic design** to improve student well-being and personal fitness.

The suite consists of:

1. **Sleep Quality & Well-being Tracker** – Provides tailored advice based on user-reported sleep data.  
2. **ML-Powered Fitness & Activity Tracker** – Processes sensor data to calculate fitness metrics and classify physical activities using a trained machine learning model.

Our goal is to emphasize **algorithmic design** and **meaningful data representation** to help users focus effectively on their health and fitness goals.

---

## ✨ Key Features

### 1. Sleep Quality & Well-being Tracker
- **User-Rated Input**: Prompts users to rate their sleep quality.
- **Tailored Advice**: Provides customized insights and recommendations to encourage healthier sleep habits.

### 2. ML-Powered Fitness & Activity Tracker
- **Multi-Sensor Data Capture**: Processes GPS and accelerometer data collected during physical activity.
- **Key Metric Calculation**: Accurately calculates:
  - Step Count
  - Total Distance Traveled
  - Estimated Calories Burned
- **Activity Classification (ML Model)**: Uses a machine learning model to classify activities (e.g., sitting, walking, running) with higher accuracy than simple velocity thresholds.
- **Path Visualization**: Visualizes the journey taken during the activity.
- **Modular Design**: Users can run all modules together for a comprehensive summary or extract specific statistics individually.

---

## 🛠 Technology Stack
- **Core Language**: MATLAB
- **Data Processing**: MATLAB built-in functions for handling GPS and accelerometer data
- **Machine Learning**: MATLAB Statistics and Machine Learning Toolbox for training the activity classification model

---

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- MATLAB (R2019a or later recommended)
- MATLAB Statistics and Machine Learning Toolbox

### Installation and Setup
1. **Clone the Repository**
```bash
git clone [Your Repository URL Here]
cd health-wellness-tracking-suite
