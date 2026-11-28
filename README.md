# SmartRide AI – Intelligent Bike-Sharing Demand Forecasting System

## Project Overview

SmartRide AI is a machine learning-based application designed to analyse historical bike-sharing demand and predict future bicycle rental demand.

The system aims to help bike-sharing operators understand rental patterns, identify high-demand and low-demand periods, and make better operational planning decisions.

## Project Objectives

- Analyse historical bike rental demand.
- Identify demand patterns based on time and weather conditions.
- Predict hourly bike rental demand using machine learning.
- Evaluate and compare forecasting model performance.
- Provide operational insights based on predicted demand.

## Main Modules

### 1. Demand Analysis Dashboard
Visualise historical bike rental patterns, hourly demand, daily trends, and weather-related demand patterns.

### 2. AI Demand Forecasting
Develop and evaluate machine learning models to predict hourly bike rental demand.

### 3. Operational Insights
Identify expected high-demand and low-demand periods and provide recommendations for bike availability planning.

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

Bike Sharing Demand dataset – UCI Bike Sharing Dataset.

The dataset contains hourly bike rental records and associated weather and calendar information.

## Project Architecture

React.js → Java Spring Boot → Python FastAPI → Machine Learning Model

PostgreSQL will be used for application data and prediction history.

## Project Status

Currently in the initial setup and dataset exploration stage.

## Project Structure

- `frontend/` – React application
- `backend/java-api/` – Spring Boot backend
- `backend/ml-service/` – Python ML service
- `notebooks/` – Data exploration and experiments
- `dataset/` – Raw and processed datasets
- `models/` – Trained machine learning models
- `documentation/` – Project documentation

## Project Goal

To develop an end-to-end AI-powered bike-sharing demand forecasting application while applying machine learning and full-stack development concepts.