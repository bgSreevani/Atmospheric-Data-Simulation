# Large-Scale Atmospheric Data Simulation via Parallel Processing
# AI-Powered Weather Intelligence Platform (HPC Project)
## Project Overview
This project presents a High Performance Computing (HPC)-based atmospheric data simulation system designed to process and analyze large-scale weather data efficiently.
It focuses on:
* Weather prediction
* Atmospheric data analysis
* Future forecasting using Deep Learning (LSTM)
* High-speed computation using parallel processing
The system integrates machine learning, deep learning, and parallel computing with an interactive web interface to simulate and visualize atmospheric conditions.
## Google Colab Notebook
https://colab.research.google.com/drive/1w-ckCcWs26cqaYCmPAFV9KjuwyTZYJjr?usp=sharing
## Dataset
https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data/data?utm_source=chatgpt.com
## Technologies Used
*  Python 3.x
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras (LSTM)
* Matplotlib
* Gradio (Web Interface)
* Multiprocessing (Parallel Computing)
## Key Features
* Atmospheric temperature prediction using ML
* LSTM-based future forecasting
* Parallel data processing (HPC concept)
* Time-series visualization
* Interactive Gradio dashboard
* Multi-city simulation
* Real-time prediction experience
## System Architecture
* User selects city via web interface
* Input sent to backend (Gradio)
* Data preprocessing and cleaning
* Parallel processing using multiprocessing
* ML & LSTM models applied
* Predictions and graphs generated
* Results displayed to user
## Installation and Setup
git clone https://github.com/your-username/atmospheric-hpc-project.git
cd atmospheric-hpc-project
## Install Dependencies
pip install pandas numpy matplotlib scikit-learn tensorflow gradio
## How to Run
### Option 1: Google Colab (Recommended)
* Open notebook
* Upload dataset
* Run all cells
* Access Gradio interface
### Option 2: Local Execution
python weather.py
Then open the Gradio link shown in terminal.
## Output
The system produces:
* ML Predicted Temperature
* LSTM Future Forecast
* Temperature Trend Graph
* City-based simulation results
## Sample Output Fields
* City
* Temperature Prediction
* Forecast Value
* Date/Time
* Visualization Graph
## HPC Concepts Applied
* Parallel processing using multiprocessing
* Data chunking for large-scale datasets
* Efficient time-series computation
* Hybrid ML + Deep Learning models
## Future Enhancements
* Real-time API integration
* Cloud deployment (AWS / Azure)
* Mobile-friendly interface
* Advanced models (GRU, XGBoost)
* Global atmospheric datasets
## Author
BG Sreevani
## References
* TensorFlow Documentation
* Scikit-learn Documentation
* Gradio Documentation
* Pandas Documentation
