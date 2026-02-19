# 🌦️ Hybrid Prophet-XGBoost Framework for High-Precision Climate Forecasting

[![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue)](https://www.kaggle.com/datasets/gmbiggan/climate-data)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-orange)](https://www.kaggle.com/code/gmbiggan/a-hybrid-prophet-xgboost-framework-for-high-precis)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)

## 📋 Project Overview

This project presents a **hybrid forecasting framework** combining Facebook Prophet and XGBoost to analyze and predict climate patterns in hill regions from 1981 to 2040.

### 🎯 Key Objectives
- Analyze 44 years of historical climate data (1981-2025)
- Generate 15-year future forecasts (2026-2040) with 95% confidence
- Predict temperature, precipitation, and humidity patterns
- Identify climate change impacts in hill region ecosystems

## 🔬 Methodology

### 🤖 Hybrid Architecture
- **Facebook Prophet**: Temperature & humidity forecasting (captures seasonality)
- **XGBoost**: Precipitation prediction (handles non-linear patterns)

### 📊 Model Performance
| Parameter | Accuracy Metric | Value |
|-----------|-----------------|-------|
| Temperature | MAPE | 1.6% - 2.5% |
| Rainfall | RMSE | 0.45 mm |
| Humidity | Accuracy | 96.2% |
| Confidence Interval | - | 95% |

## 🔍 Key Findings

### 📈 Temperature Trend
- **0.54°C** temperature increase projected by 2040
- Consistent warming observed across all seasons
- Winter months warming faster than summer

### 🌧️ Precipitation Pattern
- **12.5%** increase in rainfall variability
- More erratic monsoon patterns
- Increased flash flood risk in hill regions

### 💧 Humidity Shift
- **+2.3%** humidity increase by 2040
- Higher heat index affecting human comfort
- Changes in ecosystem transpiration rates

## 🗂️ Repository Structure
