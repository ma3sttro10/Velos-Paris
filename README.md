# Bike Station Occupancy Prediction Dashboard

An interactive web application for analyzing and predicting bike station occupancy rates in real-time using machine learning techniques.

## Overview

This dashboard allows users to:
- Visualize and compare actual vs predicted occupancy rates for any bike station
- Select different prediction parameters and features
- View model performance metrics and station correlations
- Analyze temporal patterns in station usage

## Features

### Interactive Controls
- Station selection dropdown
- Adjustable number of predictive stations (3-15)
- Temporal feature selection:
  - Hour of day
  - Day of week
  - Weekend indicator
- Customizable time window (24-240 hours)

### Visualization
- Real-time comparison graphs
- Model performance statistics:
  - Mean Squared Error (MSE)
  - R² Score
  - Most influential stations

## Installation

1. Install required packages:
```bash
pip install dash dash-bootstrap-components pandas numpy plotly scikit-learn
