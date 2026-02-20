
Daily Tea Harvest Yield Predictor

The Daily Tea Harvest Yield Predictor is a practical tool that helps tea farmers estimate their daily harvest based on key factors such as the number of workers, rainfall, and temperature. It uses Python, scikit-learn, and SQLite to manage data, make predictions, and store results in a database. This project demonstrates a full workflow — from data collection and storage to calculation and record-keeping — giving farmers insights to plan resources and track productivity.

Key Features

Data Storage: Efficiently manages farm data using SQLite.

Yield Prediction: Estimates daily tea harvest based on collected factors.

Data Management: Saves predictions back to the database for easy tracking.

Practical Workflow: Covers the full process of gathering data, running calculations, and storing results.

Getting Started

Follow these steps to set up and run the project locally:

Clone the Repository

git clone [repository-url]

Install Dependencies

pip install -r requirements.txt

Run the Notebook
Open yield_prediction.ipynb in VS Code (or Jupyter) and run the cells to see the predictions.

How It Works

Data is collected from the farm (workers, rainfall, temperature, and actual harvest).

A model calculates estimated yields based on the input factors.

Predictions are saved back to the SQLite database for review and analysis.

This project provides a straightforward example of how structured data can support practical farm decisions.



