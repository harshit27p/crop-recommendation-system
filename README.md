# 🌾 Crop_AI - Crop Recommendation System using IBM watsonx.ai

## 🧠 Project Overview

**Crop_AI** is an AI-based crop recommendation system built entirely on **IBM Cloud** using **watsonx.ai Studio**. The goal is to assist farmers and agricultural analysts by suggesting the most suitable crops to grow based on soil and environmental conditions.

This project does **not use programming languages** like Python locally. Instead, it leverages **IBM's visual tools and AutoAI features** to build, train, and deploy a machine learning model via cloud services.

---

## 🎯 Objective

Recommend the best crops based on:
- Soil nutrients (N, P, K)
- Temperature
- Humidity
- pH level
- Rainfall

---

## 🛠️ Tools & Services Used

| IBM Cloud Service | Description |
|-------------------|-------------|
| **watsonx.ai Studio** | Cloud-based AI environment for model building and deployment |
| **Cloud Object Storage** | Stores datasets and project artifacts |
| **AutoAI** | Automatically selects and trains the best machine learning model |
| **Deployments** | Makes the model accessible via API or web service |

---

## 📊 Dataset Information

The dataset includes the following features:
- **N**: Nitrogen content in soil
- **P**: Phosphorus content
- **K**: Potassium content
- **Temperature**: in Celsius
- **Humidity**: in percentage
- **pH**: Soil pH value
- **Rainfall**: in mm
- **Label**: Crop name (target variable)

---

## 🔁 Workflow

1. **Created Project** in watsonx.ai Studio
2. **Uploaded Dataset** to Cloud Object Storage
3. **Ran AutoAI Experiment** using the uploaded data
4. **Trained & Evaluated Models** visually (no coding)
5. **Deployed the Best Model** as a web service
6. **Generated API endpoint** for integration (optional)

---

## 🚀 Features

- No-code model training with AutoAI
- Cloud-hosted and scalable
- Easy deployment and access
- Can be extended to mobile or web applications

---

## 📂 Project Structure

Crop_AI/
├── Dataset (uploaded in cloud)
├── AutoAI Experiment
├── Trained Model (Auto-generated)
├── Deployment (Web service)
└── Report.pdf (this file)

## 📎 Resources

- 🔗 [IBM watsonx.ai Documentation](https://www.ibm.com/docs/en/watsonx)
- 📊 Dataset Source: Publicly available crop datasets (e.g., Kaggle)
- 🧠 Powered by: IBM Cloud

---

## 👤 Author

**Project by:** Harshit Prajapati
**Platform:** IBM SkillsBuild / Edunet Foundation  
**Date:** July 2025
