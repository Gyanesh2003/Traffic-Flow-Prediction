# Traffic Flow Prediction

A machine learning project that predicts traffic flow using Random Forest and Support Vector Regression (SVR) models.

## Overview

This project implements a traffic flow prediction system that uses historical traffic data to predict future traffic patterns. It compares the performance of two different machine learning algorithms:
- Random Forest Regressor
- Support Vector Regression (SVR)

## Features

- Data preprocessing and normalization
- Traffic flow prediction using multiple features
- Model accuracy comparison
- Error rate analysis
- Automated prediction rounding based on threshold values

## Requirements

python
pandas
numpy
matplotlib
scikit-learn

## Installation

1. Clone the repository
git clone https://github.com/yourusername/traffic-flow-prediction.git
cd traffic-flow-prediction

2. Install required packages
## Dataset

The project uses a traffic flow dataset (`trafficflow.csv`) that should contain the following columns:
- Date
- Additional features (columns 2-5)
- Target variable (column 6)

Place your dataset in the project root directory.

## Usage

Run the main script:
The script will:
1. Load and preprocess the data
2. Train both Random Forest and SVR models
3. Make predictions
4. Display accuracy metrics for both models

## Model Performance

The system evaluates model performance using:
- Error percentage
- Accuracy percentage

Both models include automatic rounding adjustments based on a 2.5 threshold value to improve prediction accuracy.

## Project Structure
Traffic Flow Prediction/
│
├── public/
│ └── traffic_flow.py # Main prediction script
│
├── data/
│ └── trafficflow.csv # Dataset (not included)
│
├── README.md
└── requirements.txt

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to anyone whose code was used
- Any research papers referenced
- Any other acknowledgments

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/traffic-flow-prediction](https://github.com/yourusername/traffic-flow-prediction)
