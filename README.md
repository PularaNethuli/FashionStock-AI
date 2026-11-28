# SmartRide AI – AI-Powered Bike-Sharing Demand Forecasting and Operational Insights System

## Project Overview

SmartRide AI is a machine learning-based application designed to analyse historical bike-sharing demand and predict hourly bicycle rental demand.

The system aims to help bike-sharing operators understand rental patterns, identify high-demand and low-demand periods, and make better operational planning decisions using historical data and machine learning predictions.

## Project Objectives

- Analyse historical bike rental demand.
- Identify demand patterns based on time, seasons, and weather conditions.
- Predict hourly bike rental demand using machine learning.
- Evaluate forecasting models using appropriate performance metrics.
- Provide operational insights based on predicted demand.

## Main Modules

### 1. Demand Analysis Dashboard

Visualise historical bike rental patterns, hourly demand, seasonal trends, and weather-related demand patterns.

### 2. AI Demand Forecasting

Develop and evaluate machine learning models to predict hourly bike rental demand.

Planned approaches:
- Moving Average (baseline model)
- Random Forest Regression

Model performance will be evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### 3. Operational Insights

Identify expected high-demand and low-demand periods and provide suggestions to support bike availability planning.

These insights will be based on predicted overall rental demand rather than individual station inventory.

## Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Main Backend | Java, Spring Boot |
| ML Service | Python, FastAPI |
| Database | PostgreSQL |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Visualisation | Plotly |

## Dataset

**Dataset:** Seoul Bike Sharing Demand

**Source:** UCI Machine Learning Repository

**File:** `SeoulBikeData.csv`

The dataset contains 8,760 hourly observations of bike rentals in Seoul, along with weather conditions, seasons, holidays, and other relevant information.

**Target Variable:** `Rented Bike Count`

**Dataset Link:** https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand

**License:** CC BY 4.0

## Project Architecture

React.js → Java Spring Boot → Python FastAPI → Machine Learning Model

PostgreSQL will be used to store application data and prediction history.

## Project Status

Currently in the initial setup and dataset exploration stage.

## Project Structure

- `frontend/` – React application
- `backend/java-api/` – Spring Boot backend
- `backend/ml-service/` – Python ML service
- `notebooks/` – Data exploration and experiments
- `dataset/raw/` – Original dataset
- `dataset/processed/` – Cleaned and processed dataset
- `models/` – Trained machine learning models
- `documentation/` – Project documentation

## Project Goal

To develop an end-to-end AI-powered bike-sharing demand forecasting application while gaining practical experience in machine learning, data analysis, backend development, and frontend integration.