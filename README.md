# 🚨 Helmet Violation Detection System

This project aims to automate the detection of **motorcycle helmet violations** using computer vision and machine learning. It identifies **riders not wearing helmets**, extracts their **vehicle number plates**, and logs the data for enforcement in both **CSV files** and a **MySQL database**.

## 🎯 Problem Statement

Manual enforcement of helmet laws is resource-intensive and prone to human error. This project introduces an AI-powered solution for detecting violations in real-time from traffic surveillance footage.

## ✅ Solution Overview

- **Helmet Detection** using YOLOv8
- **Number Plate Localization** via OpenCV
- **Data Logging** into:
  - `.csv` files (for quick local logs)
  - `MySQL` database (for scalable, centralized access)

### 📁 Inputs:
- Traffic surveillance videos

### 📄 Outputs:
- Logged number plates of non-helmet riders
- Stored in `Models.zip` directory (final trained models)

## 🧠 Technologies Used

- `YOLOv8` – Object Detection for helmets
- `OpenCV` – Frame and plate processing
- `TensorFlow`, `Scikit-Learn` – Supporting model training
- `MySQL`, `Pandas` – Data logging and CSV generation

## 📦 Trained Models

You can find the **final trained models** in the repository under


## ⚠️ Code & Data Policy

Please note that the **source code and raw data** for this project **cannot be shared publicly** due to a signed **Non-Objection Certificate (NOC)** agreement. Only model weights and demo videos are included in this repository.

## 📹 Demo Videos

- `Signal.mp4`
- `Signal Video 2.mp4`

These videos showcase the detection and number plate capture in real-time traffic scenarios.

---

> 📬 For collaborations or further information, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/maithiltandel/).
