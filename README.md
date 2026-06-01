# Traffic-Signal-Optimization-Using-Artificial-Intelligence

# Traffic Signal Optimization Using Artificial Intelligence 🚦

## Overview

Traffic congestion is one of the major challenges faced by modern cities. Traditional traffic signal systems operate on fixed timing schedules, which often fail to adapt to changing traffic conditions. This project introduces an AI-based Traffic Signal Optimization System that dynamically adjusts signal timings based on real-time traffic density.

Using Machine Learning techniques, the system analyzes vehicle density from four directions (North, South, East, and West) and predicts the optimal green signal time to improve traffic flow and reduce congestion.

---

## Features

* Real-time traffic density analysis
* AI-based signal timing prediction
* Dynamic traffic signal optimization
* Traffic data visualization
* Machine Learning model using Random Forest Regressor
* Performance evaluation using MAE and R² Score
* Graphical representation of traffic patterns

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Project Structure

```text
Traffic-Signal-Optimization-AI/
│
├── traffic_signal_dataset.csv
├── traffic_signal_optimization.ipynb
├── README.md
└── images/
    ├── traffic_density_graph.png
    ├── feature_importance.png
    ├── correlation_heatmap.png
    └── model_performance.png
```

---

## Dataset

The dataset contains traffic density information from four directions:

| Feature    | Description                   |
| ---------- | ----------------------------- |
| North      | Vehicles from North direction |
| South      | Vehicles from South direction |
| East       | Vehicles from East direction  |
| West       | Vehicles from West direction  |
| Green_Time | Optimal signal time (seconds) |

---

## Machine Learning Model

The project uses a Random Forest Regressor to predict the optimal green signal time based on traffic density.

### Workflow

1. Load dataset
2. Data preprocessing
3. Data visualization
4. Model training
5. Signal time prediction
6. Performance evaluation
7. Result visualization

---

## Results

The model successfully predicts optimal green signal timings and helps in:

* Reducing traffic congestion
* Decreasing vehicle waiting time
* Lowering fuel consumption
* Reducing carbon emissions
* Improving urban mobility

Generated Visualizations:

* Average Traffic Density Graph
* Actual vs Predicted Green Time
* Feature Importance Analysis
* Correlation Heatmap
* Traffic Distribution Histogram
* Model Performance Metrics

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Traffic-Signal-Optimization-AI.git
```

Move into the project directory:

```bash
cd Traffic-Signal-Optimization-AI
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Usage

Run the Jupyter Notebook or Google Colab notebook:

```bash
jupyter notebook
```

Upload the dataset and execute all cells to train the model and generate predictions.

---

## Future Enhancements

* Real-time traffic monitoring using CCTV cameras
* Vehicle detection with OpenCV
* Object detection using YOLO
* IoT sensor integration
* Emergency vehicle prioritization
* Smart city dashboard implementation

---

## Conclusion

This project demonstrates how Artificial Intelligence and Machine Learning can be integrated into transportation systems to optimize traffic signal timings. The proposed solution improves traffic flow, reduces congestion, and contributes to smarter and more sustainable urban transportation.

---

## Author

Hemasai & Team

B.Tech Engineering Student

AI & Machine Learning Enthusiast 

---

## License

This project is developed for educational and research purposes. Feel free to use and modify it for learning and academic projects.
