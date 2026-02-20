# MotionAlert: Wearable Seizure Monitoring

## **Project Overview**
MotionAlert is an advanced seizure detection system using wearable accelerometer data. This project detects abnormal movement patterns, calculates high activity duration, and simulates caregiver alerts based on real-time peaks and clusters. It provides visualization and statistical summaries for better understanding of seizure events.

---

## **Features**
- **Peak Detection**: Identifies sudden spikes in movement corresponding to possible seizure activity.  
- **High Activity Duration**: Calculates the duration of abnormal movement in samples, seconds, and minutes.  
- **Caregiver Alert Simulation**: Highlights clusters of continuous high activity (>5 seconds) that may require attention.  
- **Statistical Insights**: Mean, max, min of peak magnitudes and average interval between peaks.  
- **Visualization**: Interactive plots showing filtered acceleration magnitude, moving averages, detected peaks, and high activity zones.  
- **Energy Analysis**: Computes movement energy over a sliding window to quantify intensity.  

---

## **Dataset**
- Expected CSV format: Columns `x`, `y`, `z` for accelerometer readings.  

